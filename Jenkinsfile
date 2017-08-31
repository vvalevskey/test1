#!groovy
@Library(['github.com/docker/jenkins-pipeline-scripts'])
import groovy.transform.InheritConstructors

@InheritConstructors
class DeployTimeoutException extends Exception {
}

try {
  steps.timestamps {
    stage('docker-cloud') {
      node {
        docker.withServer('tcp://54.242.67.234:2375'){
           sh "docker ps"  
        }
      }
    }
  }
}

#!groovy
@Library(['github.com/docker/jenkins-pipeline-scripts'])

try {
  stage {
    node('docker-cloud') {
      docker.withServer('tcp://54.242.67.234:2375'){
         sh "docker ps"  
      }
    }
  }
}

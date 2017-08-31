#!groovy

try {
  steps.timestamps {
    stage('docker-cloud') {
      node {
        docker.withServer('tcp://54.242.67.234:2375'){
           
        }
      }
    }
  }
} catch (err) {
    echo err.message.toString()
    manager.buildFailure()
}

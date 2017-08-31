node('docker-cloud') {
  docker.withServer('tcp://127.0.0.1:2376', 'my-docker-creds'){
     sh "docker ps"  
  }
}

agent any

environment {
  registryName = "myakacregistry"
}

stages {
  
  stage ('Build Docker image') {
    steps { 
      
      script {
        dockerImage = docker.build registryName
      }
    }
  }
}

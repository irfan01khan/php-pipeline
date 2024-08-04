pipeline {
  agent {
    label "docker-agent"
  }
  stages {
    stages {
     stage {'Run Docker Compose'} {
       steps{
         sh 'sudo docker-compose up -d'
       }
     }
    }
  }          
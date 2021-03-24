pipeline{
  agent {
    docker {
      image "node:8-alpine"
    }  
  }
  stages {
    stage("Build")  {
      steps  {
        sh "docker ps"
        sh "npm install"
      }
    }
  }
}

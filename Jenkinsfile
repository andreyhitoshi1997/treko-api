pipeline{
  agent {
    docker {
      image "node:8-alpine"
    }  
  }
  stages {
    stage("Build")  {
      steps  {
        sh "docker run --privileged -v /var/run/docker.sock:/var/run/docker.sock",
        sh "npm install"
      }
    }
  }
}

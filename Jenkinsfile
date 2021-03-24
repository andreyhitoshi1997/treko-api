pipeline{
  agent {
    docker {
     docker run --privileged -v /var/run/docker.sock:/var/run/docker.sock
      image "node:8-alpine"
    }  
  }
  stages {
    stage("Build")  {
      steps  {
        sh "npm install"
      }
    }
  }
}

pipeline {
  agent any
  stages{
  
    stage("Build") {
      script {  
        image = docker.build("myimage")
      }
    }
    stage("Test") {
      script {
        image.run()
      }
    }
  }
}

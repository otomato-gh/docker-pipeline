pipeline {
  agent any
  stages{
  
    stage("Build") {
      steps{ 
        script {  
          image = docker.build("myimage")
        }
      }
    }
    stage("Test") {
      steps {
        script {
          image.run()
        }
      }
    }
  }
}

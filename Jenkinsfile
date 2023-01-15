node {
  scm checkout
  stage("Build") {
    image = docker.build("myimage")
  }
  stage("Test") {
    image.run()
  }
}

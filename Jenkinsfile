pipeline{
  agent any
  stages{
    steps("Build") {
      bat "javac Hello.java"
    }
    steps("Run") {
      bat "java Hello"
    }
  }
}

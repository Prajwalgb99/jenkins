pipeline{
  agent any

  stages{
    stage('compile java program'){
      stepa{
        bat 'javac Helloworld.java'
      }
      stage('Run Java program'){
        steps{
          bat 'java Helloworld'
        }
      }
    }
  }
}

pipeline {
    agent any

    stages {
        stage('Compile Java Program') {
            steps {
                bat 'javac Helloworld.java'
            }
        }

        stage('Run Java Program') {
            steps {
                bat 'java Helloworld'
            }
        }
    }
}

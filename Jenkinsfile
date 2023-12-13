pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                git 'https://github.com/sufyanahmed1310/HelloWorld.git'
            }
        }
        stage('Java') {
            steps {
                sh '''javac Hello.java
                java Hello'''
            }
        }
    }
}

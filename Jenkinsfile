pipeline {
    agent {
        label ('newSlave')
    }

    stages {
        stage('Hello') {
            steps {
                git 'https://github.com/sufyanahmed1310/HelloWorld.git'
            }
        }
        stage('Java') {
            steps {
                sh '''java Hello.java'''
            }
        }
    }
}

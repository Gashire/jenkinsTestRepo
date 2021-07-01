pipeline {
    agent none

    stages {
        stage('Setup') {
            steps {
                sh 'python --version'
            }
        }
        stage('Test') {
            steps {
                sh 'git --version'
            }
        }
    }
}
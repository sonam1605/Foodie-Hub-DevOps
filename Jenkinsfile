pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Verify Environment') {
            steps {
                sh 'pwd'
                sh 'ls -la'
                sh 'git --version'
                sh 'docker --version'
            }
        }
    }
}
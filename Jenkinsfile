pipeline {
    agent {
        label 'docker-agent'
    }

    stages {
        stage('Checkout') {
            steps {
                echo 'Source code sudah di-checkout oleh Jenkins'
            }
        }

        stage('Environment') {
            steps {
                sh 'echo "Running on:"'
                sh 'hostname'
                sh 'whoami'
                sh 'pwd'
                sh 'ls -la'
            }
        }

        stage('Build') {
            steps {
                echo 'Build application...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }

        stage('Finish') {
            steps {
                echo 'Pipeline selesai!'
            }
        }
    }
}
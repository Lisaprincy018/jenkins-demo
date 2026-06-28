pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
                echo 'Checkout completed'
            }
        }

        stage('Build') {
            steps {
                echo 'Building application...'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing application...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment completed successfully!'
            }
        }
    }
}

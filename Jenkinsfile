pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Checkout the source code from your version control system (e.g., Git).
                checkout scm
            }
        }
        stage('Build and Test') {
            steps {
                // Replace this with the actual build and test commands for your application.
                sh 'echo "Building and testing the project"'
            }
        }
    }

    post {
        success {
            echo 'Pipeline succeeded!'
        }
        failure {
            echo 'Pipeline failed!'
        }
    }
}

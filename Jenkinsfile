pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    echo 'Building...'
                    sh 'npm install'  // Install dependencies
                }
            }
        }
        stage('Test') {
            steps {
                script {
                    echo 'Testing...'
                    sh 'npm test'  // Run tests
                }
            }
        }
        stage('Deploy') {
            steps {
                script {
                    echo 'Deploying...'
                    // Add deployment commands here
                }
            }
        }
    }
}

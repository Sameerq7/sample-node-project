pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    echo 'Building...'
                    bat 'npm install'  // Install dependencies on Windows
                }
            }
        }
        stage('Test') {
            steps {
                script {
                    echo 'Testing...'
                    bat 'npm test'  // Run tests on Windows
                }
            }
        }
        stage('Deploy') {
            steps {
                script {
                    echo 'Deploying...'
                    // Add Windows deployment commands here
                }
            }
        }
    }
}

pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Saad-Abdulah/SCD_Activity-6.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project...'
                sh 'npm install'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'npm test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}

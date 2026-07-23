pipeline {
    agent any

    stages {

        stage('Checkout Code') {
            steps {
                echo 'Checking out OrangeHRM source code'
            }
        }

        stage('Build Docker Image') {
            steps {
                sh 'docker build -t orangehrm-app .'
            }
        }

    }
}
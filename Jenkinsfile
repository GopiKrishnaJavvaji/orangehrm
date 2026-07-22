pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Getting OrangeHRM source code'
            }
        }

        stage('Build') {
            steps {
                echo 'Building Docker image'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying OrangeHRM application'
            }
        }
    }
}
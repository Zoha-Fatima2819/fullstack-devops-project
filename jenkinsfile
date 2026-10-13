pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Getting code from GitHub'
            }
        }

        stage('Build') {
            steps {
                echo 'Docker Compose Build'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy Application'
            }
        }

    }
}

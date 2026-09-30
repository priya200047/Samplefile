pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
            }
        }

      stage('checkout') {
            steps {
                checkout scm
            }
        }

    stage('Deploy') {
            steps {
                echo 'Deploying the application...'
            }
        }
    }
}

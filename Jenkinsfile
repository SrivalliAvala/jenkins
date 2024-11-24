pipeline {
    agent any
    options {
        // Timeout counter starts AFTER agent is allocated
        timeout(time: 1, unit: 'SECONDS')
    }
    stages {
        stage('Build') {
            steps {
                echo 'this is build stage'
            }
        }
        stage('Test') {
            steps {
                echo 'this is test stage'
            }
        }
        stage('Deploy') {
            steps {
                echo 'this is deploy stage'
            }
        }
    }
}
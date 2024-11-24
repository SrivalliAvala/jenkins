pipeline {
    agent any
    options {
        // Timeout counter starts AFTER agent is allocated
        timeout(time: 1, unit: 'SECONDS')
    }
    stages {
        stage('Build') {
            steps {
                script{
                    echo 'this is build stage'
                }         
            }
        }
        stage('Test') {
            steps{
                script{
                    echo 'this is test stage'
                } 
            }   
        }
        stage('Deploy') {
            steps {
                script{
                    echo 'this is deploy stage'
                }
            }
        }
    }
}
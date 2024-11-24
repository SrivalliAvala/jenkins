pipeline {
    agent{
        label 'jenkins-agent'
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
    post {
        always{
            echo "This sections runs always"
            deleteDir()
        }
        success{
            echo "This section run when pipeline success"
        }
        failure{
            echo "This section run when pipeline failure"
        }
    }
}
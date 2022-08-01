#!groovy

properties([disableConcurrentBuilds()])

pipeline{
    agent any
    
    options {
        timestamps()
    }
    
    stages{
        stage("Test stage") {
            steps {
                echo "========== Start Test stage =========="
                sh 'hostname'
                sh 'pwd'
                sh 'id'
            }
        }
    }
}

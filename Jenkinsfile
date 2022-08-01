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
                Credentials([string(credentialsId: 'passwrod123', variable: 'paswd')]){
                    sh 'echo ${passwd}'
                }
                sh 'hostname'
                sh 'pwd'
                sh 'id'
            }
        }
    }
}

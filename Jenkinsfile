pipeline{
    agent any
    stages{
        stage('Checkout Code'){
            steps{
                checkout scm
                
            }
        }
        stage('Run Python Script'){
            steps{
                script{
                    sh 'python3 test1.py'
                }
            }
        }
    }
}
pipeline{
    Agent any
    Stages{
        stage('Checkout Code'){
            steps{
                checkout scm
                
            }
        }
        stage('Run Python Script'){
            steps{
                script{
                    sh 'python test.py'
                }
            }
        }
    }
}
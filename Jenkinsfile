pipeline{
    agent any
    stages{
        stage('SCM'){
            steps{
                              echo "getting code from SCM"
        }
        }
        stage('Build'){
            steps{
            echo "Build job"
        }
        }
        stage('Deploy'){
            steps{
            echo "Build deploy"
        }
        }
        stage('Test'){
            steps{
            echo "Acceptance Testing"
        }
        }
        stage('Release'){
            steps{
            echo "Deployment is successful"
        }
        }

            }
}

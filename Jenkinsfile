pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name jamieEKS --template-body file://eks.yaml --region 'us-east-1'"
              }
         }


     }
}

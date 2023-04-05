pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name eshani-cluster-jenkins --template-body file://automate-kubernetes.yaml --region 'us-east-1'"
              }
         }


     }
}

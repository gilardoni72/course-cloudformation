pipeline {
    agent any
    stages {
        stage('CoudFormation') {
            steps { 
                sh " aws cloudformation create-stack --stack-name MiEc3 --template-body file://2-ec2.yaml --region 'us-west-2'"
            }
        }
    }
}
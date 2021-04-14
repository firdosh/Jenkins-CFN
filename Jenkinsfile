pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh "aws cloudformation create-stack --stack-name s3bucket --template-body file://s3cft.yml --region 'us-west-2'"
      }
    }

  }
}

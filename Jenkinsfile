pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh '"aws cloudformation create-stack --stack-names3bucket --template-body file://s3cft.yaml --region 'us-west-2'"
      }
    }

  }
}

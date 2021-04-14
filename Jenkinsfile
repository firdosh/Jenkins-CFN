pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh '"aws cloudformation create-stack --stack-names3bucket --template-body file://simplests3cft.json --region \'us-west-2"'
      }
    }

  }
}
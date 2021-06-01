pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh "aws cloudformation delete-stack --stack-name s3bucket --template-body file://s3cft.yml --region 'us-west-2' --notification-arns 'arn:aws:sns:us-west-2:308773293539:snsTopic-SNSTopicEmail-3DLEXWETC0AN'"
      }
    }

  }
}

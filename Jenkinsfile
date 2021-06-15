pipeline {
  agent any
  stages {
    stage('Stage1') {
      steps {
        sh 'echo "Owner of $BUILD_NUMBER Build is $Owner"'
      }
    }

  }
  environment {
    Owner = 'Kostic'
  }
}
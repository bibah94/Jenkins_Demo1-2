pipeline {
  agent any
  stages {
    stage('Stage1') {
      steps {
        echo 'This is build $BUILD_NUMBER of project $PROJECT_NAME'
      }
    }

  }
  environment {
    PROJECT_NAME = 'DEVOPS'
  }
}
pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo '''
        Stage for $BUILD_NUMBER
        '''
      }
    }

  }
  environment {
    DEMO = '1'
  }
}

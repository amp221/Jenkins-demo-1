pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'This is build number $BUILD_NUMBER of demo $DEMO'
        sh 'echo "This is build number $BUILD_NUMBER of demo $DEMO"'
        sh 'echo "*******TEST*****"'
      }
    }

  }
  environment {
    Demo = '1'
  }
}
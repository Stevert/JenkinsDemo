pipeline {
  agent any
  stages {
    stage('stage 1') {
      steps {
        echo 'This is demo $DEMO'
        sh 'echo "This is build demo $DEMO"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}
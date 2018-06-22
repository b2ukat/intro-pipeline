pipeline {
  agent any
  stages {
    stage('Say Hello ') {
      steps {
        echo "${MY_NAME}"
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Kamal'
  }
}
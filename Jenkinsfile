pipeline {
  agent none
  stages {
    stage('Hello') {
      steps {
        echo 'Hello'
      }
    }
    stage('Build') {
      steps {
        bat 'rake build'
      }
    }
  }
}
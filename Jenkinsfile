pipeline {
  agent any
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
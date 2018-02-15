pipeline {
  agent {
    node {
      label 'localhost'
    }
    
  }
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
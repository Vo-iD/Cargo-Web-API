pipeline {
  agent {
    node {
      label 'assda'
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
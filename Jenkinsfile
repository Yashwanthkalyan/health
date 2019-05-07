pipeline {
  agent any
  stages {
    stage('Buiild') {
      steps {
        echo 'Building '
      }
    }
    stage('QA') {
      steps {
        echo 'QA'
      }
    }
    stage('Deploy') {
      steps {
        echo 'deploying my app'
      }
    }
  }
  environment {
    name = 'value'
  }
}
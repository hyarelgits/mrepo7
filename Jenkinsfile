pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        sh '''echo $PWD
'''
      }
    }

    stage('Deploy') {
      steps {
        echo 'Hi Test deployed now'
      }
    }

  }
}
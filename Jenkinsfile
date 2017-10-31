pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo welcome'
        timeout(time: 15)
      }
    }
    stage('Build2') {
      steps {
        sh 'echo Welcome2'
      }
    }
    stage('End') {
      steps {
        sh 'echo end'
      }
    }
  }
}
pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sleep 5
      }
    }
    stage('Test') {
      steps {
        echo 'all fail'
      }
    }
    stage('Unit') {
      steps {
        sh '''CONSOLE_RED="\\033[2;31m"
CONSOLE_GREEN="\\033[2;32m"
CONSOLE_CLEAR="\\033[0m"'''
      }
    }
  }
}
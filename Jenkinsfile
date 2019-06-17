pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sleep 5
          }
        }
        stage('Rest') {
          steps {
            sleep(time: 1, unit: 'MINUTES')
          }
        }
        stage('Terminate') {
          steps {
            echo 'Terminatation'
          }
        }
      }
    }
    stage('Test') {
      steps {
        echo 'all is well and  fail'
      }
    }
    stage('Unit') {
      steps {
        echo 'hii'
      }
    }
  }
}
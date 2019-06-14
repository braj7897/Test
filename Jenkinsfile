pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sleep 5
        retry(count: 7) {
          retry(count: 6)
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
pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sleep 5
      }
    }
    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo 'all is well and  fail'
          }
        }
        stage('Rest') {
          steps {
            sleep 1
          }
        }
        stage('html') {
          steps {
            fileExists 'D:\\Websites\\AspNetCore-master\\AspNetCore-master'
          }
        }
      }
    }
    stage('Unit') {
      parallel {
        stage('Unit') {
          steps {
            echo 'hii'
          }
        }
        stage('call') {
          steps {
            echo 'calllllllllllllllllllllllllllllllllllllllllllllll'
          }
        }
      }
    }
  }
}
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
            sleep(time: 1, unit: 'NANOSECONDS')
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
            sleep(time: 1, unit: 'NANOSECONDS')
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

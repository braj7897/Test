pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''pipeline {
    agent any
    stages {
        stage(\'Build\') {
            steps {
                bat \'set\'
            }
        }
    }
}'''
        }
      }
    }
  }
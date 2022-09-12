pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'python3 --version'
      }
    }
    stage('Frist run') {
      steps {
        sh 'python3 hello.py'
      }
    }
  }
}

pipeline {
  agent any
  stages {
    stage('BUILD') {
      parallel {
        stage('BUILD') {
          steps {
            echo 'ALI'
          }
        }
        stage('DOWNLOAD') {
          steps {
            echo 'SHAHUL DOWNLOAD'
          }
        }
      }
    }
    stage('TEST') {
      steps {
        build 'anis'
      }
    }
  }
  environment {
    name = 'ALI'
  }
}
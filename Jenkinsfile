pipeline {
  agent {
    docker {
      image 'owasp/zap2docker-stable'
      args '-d -t --name jenkinzap'
    }

  }
  stages {
    stage('build') {
      parallel {
        stage('build') {
          agent any
          steps {
            echo 'hello worl ?'
          }
        }
        stage('') {
          steps {
            sh 'zapr --summary http://192.168.222.177/mutillidae/'
          }
        }
      }
    }
  }
}
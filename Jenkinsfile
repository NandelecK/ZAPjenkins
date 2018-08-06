pipeline {
  agent {
    docker {
      image 'owasp/zap2docker-stable'
      args '-d -t --name jenkinZAP'
    }

  }
  stages {
    stage('build') {
      agent any
      steps {
        echo 'hello worl ?'
      }
    }
  }
}
pipeline {
  agent {
    docker {
      image 'owasp/zap2docker-stable'
      args '-d -t --name jenkinszap'
    }

  }
  stages {
    stage('build') {
      agent any
      steps {
        echo 'hello world ?'
      }
    }
  }
}
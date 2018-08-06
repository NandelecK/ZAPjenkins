pipeline {
  agent {
    docker {
      image 'owasp/zap2docker-stable'
      args '-d -t -p 8090:8080--name jenkinszap'
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
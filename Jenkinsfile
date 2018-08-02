pipeline {
  agent {
    docker {
      image 'hello-world'
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
pipeline {
  agent {
    docker {
      image 'docker'
    }

  }
  stages {
    stage('error') {
      steps {
        sh 'docker build -t gitlab.dlvn.ai/springboot/demo1:${BUILD_ID} .'
      }
    }
  }
}
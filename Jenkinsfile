pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
    }

  }
  stages {
    stage('') {
      steps {
        sh 'docker build -t gitlab.dlvn.ai/springboot/demo1:${BUILD_ID} .'
      }
    }
  }
}
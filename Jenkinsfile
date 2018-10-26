pipeline {
  agent any
  stages {
    stage('build user service') {
      steps {
        sh 'docker image build -t userservice:1.1-$BUILD_ID User-Service'
      }
    }
  }
}
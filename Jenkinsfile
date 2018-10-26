pipeline {
  agent any
  stages {
    stage('Build User Service') {
      parallel {
        stage('Build User Service') {
          steps {
            echo 'Started building user service'
          }
        }
        stage('Build Frontend') {
          steps {
            echo 'Starting to build Frontend'
          }
        }
        stage('3') {
          steps {
            echo '3'
          }
        }
      }
    }
    stage('Build Posts Service') {
      steps {
        echo 'starting to build posts service'
      }
    }
  }
}
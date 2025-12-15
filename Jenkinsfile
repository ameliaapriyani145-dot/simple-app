pipeline {
  agent any

  stages {
    stage('Install') {
      steps {
        sh 'npm install'
      }
    }

    stage('Run App') {
      steps {
        sh 'nohup node app.js &'
      }
    }
  }
}


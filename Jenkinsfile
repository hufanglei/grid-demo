pipeline {
  agent any
  stages {
    stage('Source') {
      steps {
        git(url: 'https://github.com/hufanglei/grid-demo.git', branch: 'master')
      }
    }

    stage('Build') {
      steps {
        tool 'gradle7.6'
        sh 'echo "hello-world"'
      }
    }

  }
  environment {
    COMPLETED_MSG = 'Build Done!'
  }
}
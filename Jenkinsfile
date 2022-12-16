pipeline {
  agent any
  stages {
    stage('Source') {
      steps {
        git(url: 'https://github.com/hufanglei/grid-demo.git', branch: 'master')
      }
    }

  }
  environment {
    COMPLETED_MSG = 'Build Done!'
  }
}
pipeline {
  agent any
  stages {
    stage('buildJar') {
      steps {
        git(url: 'https://github.com/SparshJain/test', branch: 'master')
        echo 'Fetch Successful'
      }
    }
  }
  environment {
    sit = 'sit'
  }
}
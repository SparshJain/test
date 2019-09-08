pipeline {
  agent any
  stages {
    stage('buildJar') {
      steps {
        sh 'mvn install -Dmaven.test.skip=true'
        echo 'Build Successful'
        git(url: 'https://github.com/SparshJain/test', branch: 'master')
      }
    }
  }
  environment {
    sit = 'sit'
  }
}
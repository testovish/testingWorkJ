pipeline {
  agent any
  stages {
    stage('First') {
      steps {
        git(url: 'https://github.com/testovish/testingWorkJ', poll: true, changelog: true)
      }
    }
    stage('Second') {
      steps {
        echo 'OK'
      }
    }
  }
}
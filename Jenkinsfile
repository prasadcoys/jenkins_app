pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/prasadcoys/jenkins_app.git', branch: 'main')
      }
    }

    stage('Log') {
      steps {
        sh '''ls -la
cd my-app'''
      }
    }

  }
}
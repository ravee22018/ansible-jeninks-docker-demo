pipeline {
  agent any
  stages {
    stage('Prep') {
      steps {
        echo 'Echo Preparing '
      }
    }
    stage('Build') {
      steps {
        echo 'Echo Build'
      }
    }
    stage('Invoke') {
      steps {
        ansiblePlaybook '/var/echo.yml'
      }
    }
  }
}
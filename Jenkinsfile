pipeline {
  agent any
  stages {
    stage('Task1_Fetch') {
      steps {
        git(url: 'https://github.com/HemaGRepo/RemoteRepo2.git', branch: 'master')
      }
    }
    stage('Task2_Build') {
      steps {
        echo 'Building.....'
      }
    }
    stage('Task3_Test') {
      steps {
        echo 'Testing'
      }
    }
    stage('Task4_Deploy') {
      steps {
        echo 'Deploying to server'
      }
    }
  }
}
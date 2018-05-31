pipeline {
  agent any
  stages {
    stage('Success') {
      steps {
        echo 'Say Hello'
        sh '''agent {
   label \'jdk 9\'
  }'''
        }
      }
    }
  }
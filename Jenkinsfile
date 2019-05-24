pipeline {
  agent any
  stages {
    stage('error') {
      parallel {
        stage('error') {
          steps {
            sh '''println("Hello World")
'''
          }
        }
        stage('') {
          steps {
            sh 'println("Good Day")'
          }
        }
      }
    }
  }
}
pipeline {
  agent any
  stages {
    stage('Determine Directory') {
      steps {
        pwd(tmp: true)
      }
    }
    stage('Email') {
      steps {
        mail(subject: 'Success', body: 'SUCCESS!', to: 'deanveizaj@gmail.com', from: 'deanveizaj@gmail.com')
      }
    }
  }
}
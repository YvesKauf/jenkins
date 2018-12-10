pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Minute'
      }
    }
    stage('Execute') {
      steps {
        mail(subject: 'Output', body: 'Was successful', to: 'yves.kaufmann@noseryoung.ch')
      }
    }
  }
}
pipeline {
  agent any
  stages {
    stage('Development') {
      steps {
        echo 'Execute the Dev Environment'
      }
    }

    stage('QA') {
      steps {
        git(url: 'https://github.com/unceasingwaves92/Salesforce', poll: true)
      }
    }

    stage('Deployment') {
      steps {
        echo 'Deployment the code'
      }
    }

  }
}
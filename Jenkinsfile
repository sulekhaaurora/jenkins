pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build'
      }
    }

    stage('Confirm') {
      steps {
        input(message: 'Do you want to deploy to staging?', ok: 'Yes, Lets do it !')
      }
    }

  }
}
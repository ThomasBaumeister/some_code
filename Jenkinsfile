pipeline {
  agent any
  stages {
    stage('echo') {
      steps {
        echo 'hello from the trigger'
        echo 'hello'
      }
    }

  }
  triggers {
    cron('H/15 * * * *')
  }
}
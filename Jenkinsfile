pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running build automachine'
        sh './gradlew buld --no-demon'
        archiveartifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}

pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running atomation'
        sh './gradlew build --no-daemon' 
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'

      }
    }
  }
}

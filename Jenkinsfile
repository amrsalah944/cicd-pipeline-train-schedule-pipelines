pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running atomation'
        sh './gradlew build --no-daemon'
        archiveArtfacts artfacts: 'dist/trainSchedule.zip'
      }
    }
  }
}

pipeline {
  agent any
  stages {
    stage {'Build'} {
      steps {
        echo 'Running atomation'
        sh './gradlew build --nodaemon'
        archiveArtfacts artfacts: 'dist/trainSchedule.zip'
    }
  
  }

}

pipeline {
  agent any
  stages {
    stage ( "Build") {
      steps {
        echo 'Running building automation'
        sh './gradlew build --nodeamon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
     }
   }
 }

pipeline {
  agent any
  stages {
    stage ('Build'){
      echo  'Running build automation'
      sh 'gradlew build --no-deamon'
      archiveArtifacs artifacts: 'dist/trainSchedule.zip'
    }
  }
}

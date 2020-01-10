pipeline {
 agent any
 stages {
  stage ('Build') {
   steps {
    echo 'building pipeline'
    sh './gradlew build --no-daemon'
    archiveArtifacts artifacts: 'dist/trainSchedule.zip'
    }
  }
 }
}

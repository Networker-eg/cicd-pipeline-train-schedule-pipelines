pipeline {
 agent any
  stages {
    stage ('Build') {
      steps {
        echo "Running build stage..."
        sh "./gradlew build --no-daemon"
        archiveArtifact artifacts:"/dist/trainSchedule.zip"
      
      }
    
    }
  }
}
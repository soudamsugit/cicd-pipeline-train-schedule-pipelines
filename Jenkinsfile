pipeline {
agent any
  stages('Build'){
    steps {
      echo "the build is running"
      sh './gradlew build --no-daemon'
      archiveArtifacts artifacts: 'dist/trainSchedule.zip'
    }
  }
}

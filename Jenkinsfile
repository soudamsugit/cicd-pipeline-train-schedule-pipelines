pipeline {
agent any
  stages {
    stage('Build') {
      steps {
        echo "the build is running"
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }  
    }
  }
}

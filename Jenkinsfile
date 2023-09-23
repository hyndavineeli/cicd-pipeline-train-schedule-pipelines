pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
      echo 'Running Build automation Stage'
      sh './gradle daemon --no-daemon'
      archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}

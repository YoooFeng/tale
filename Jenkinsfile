pipeline {
  agent any
  stages {
    stage('Deploy') {
      steps {
        sh 'BUILD_ID=dontKillMe nohup /home/workplace/Artifacts/startup.sh &'
      }
    }
  }
}
pipeline {
  agent any
  stages {
    stage('Deploy') {
      steps {
        dir(path: '/home/workplace/Artifacts/tale') {
          sh '''nohup java -jar tale-least.jar &
ls -l'''
        }
        
      }
    }
  }
}
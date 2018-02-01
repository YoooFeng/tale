pipeline {
  agent any
  stages {
    stage('Deploy') {
      steps {
        dir(path: '/home/workplace/Artifacts/tale') {
          sh 'java -jar tale-least.jar'
        }
        
      }
    }
  }
}
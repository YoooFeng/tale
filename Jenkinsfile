pipeline {
  agent any
  stages {
    stage('Deploy') {
      steps {
        dir(path: '/home/workplace/Artifacts') {
          sh 'nohup java -jar tale-least.jar &'
        }
        
      }
    }
  }
}
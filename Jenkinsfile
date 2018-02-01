pipeline {
  agent any
  stages {
    stage('Deploy') {
      steps {
        dir(path: '/home/workplace/Artifacts/target/dist/tale') {
          sh 'nohup java -jar tale-least.jar &'
        }
        
      }
    }
  }
}
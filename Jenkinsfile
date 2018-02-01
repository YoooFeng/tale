pipeline {
  agent any
  stages {
    stage('Deploy') {
      steps {
        sh 'nohup java -jar tale-least.jar &'
      }
    }
  }
}
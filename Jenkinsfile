pipeline {
  agent any
  stages {
    stage('Deploy') {
      steps {
        sh '''pwd
ls -l
nohup java -jar tale-least.jar &'''
      }
    }
  }
}
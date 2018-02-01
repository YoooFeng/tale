pipeline {
  agent any
  stages {
    stage('Deploy') {
      steps {
        dir(path: './target/dist/tale') {
          sh '''pwd
ls -l
nohup java -jar tale-least.jar &'''
        }
        
      }
    }
  }
}
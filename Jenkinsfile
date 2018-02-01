pipeline {
  agent any
  stages {
    stage('Deploy') {
      steps {
        dir(path: './target/dist/tale') {
          sh 'ls -l'
        }
        
      }
    }
  }
}
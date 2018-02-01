pipeline {
  agent any
  stages {
    stage('Compile') {
      steps {
        sh '''mvn clean install -Pprod -DskipTests
ls -l'''
        dir(path: './target/dist/tale') {
          sh 'ls -l'
        }
        
      }
    }
  }
}
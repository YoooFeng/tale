pipeline {
  agent any
  stages {
    stage('Compile') {
      steps {
        sh 'mvn clean package -Pprod -DskipTests'
        sh '''ls -l
pwd'''
        dir(path: './target/dist/tale') {
          sh '''ls -l
pwd'''
        }
        
      }
    }
  }
}
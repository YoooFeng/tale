pipeline {
  agent any
  stages {
    stage('Compile') {
      steps {
        bat 'mvn clean package -Pprod -Dmaven.test.skip=true'
      }
    }
    stage('Deploy') {
      steps {
        dir(path: './target/dist/tale') {
          bat 'java -jar tale-least.jar'
        }
        
      }
    }
  }
}
pipeline {
  agent any
  stages {
    stage('Compile') {
      steps {
        sh 'mvn clean package -Pprod -Dmaven.test.skip=true'
      }
    }
  }
}
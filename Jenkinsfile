pipeline {
  agent any
  stages {
    stage('Compile') {
      steps {
        sh 'mvn clean package -Pprod -DskipTest'
        sleep 5
      }
    }
  }
}
pipeline {
  agent any
  stages {
    stage('Compile') {
      steps {
        sh 'mvn clean package -DskipTest'
        sleep 5
      }
    }
  }
}
pipeline {
  agent any
  stages {
    stage('Compile') {
      steps {
        sh '''mvn clean install -Pprod -DskipTests
cp -r ./target /home/workplace/Artifacts/'''
      }
    }
  }
}
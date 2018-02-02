pipeline {
  agent any
  stages {
    stage('Compile') {
      steps {
        sh '''mvn clean install -Pprod -DskipTests
cp -r ./target/dist/tale /home/workplace/Artifacts/'''
      }
    }
  }
}
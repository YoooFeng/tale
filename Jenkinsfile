pipeline {
  agent any
  stages {
    stage('Compile') {
      steps {
        sh '''pwd
ls -l
mvn clean package -Pprod -DskipTests
'''
      }
    }
  }
}
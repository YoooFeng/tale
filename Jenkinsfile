pipeline {
  agent any
  stages {
    stage('Compile') {
      steps {
        sh 'mvn clean install -Pprod -DskipTests'
        dir(path: './target/dist') {
          sh 'cp -r tale /home/workplace/Artifacts/'
        }
        
      }
    }
  }
}
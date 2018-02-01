pipeline {
  agent any
  stages {
    stage('Compile') {
      steps {
        sh 'mvn clean install -Pprod -DskipTests'
        dir(path: './target/dist/tale') {
          sh '''pwd
ls -l
cp tale-least.jar /home/workspace/Artifacts/'''
        }
        
      }
    }
  }
}
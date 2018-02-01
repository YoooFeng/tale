pipeline {
  agent any
  stages {
    stage('Compile') {
      steps {
        sh '''pwd
ls -l
mvn clean install -Pprod -DskipTests
'''
        dir(path: './target/dist/tale') {
          sh '''ls -l
cp tale-least.jar /home/workplace/Github/blueocean-plugin/blueocean/work/jobs/tale/branches/master/workspace/'''
        }
        
      }
    }
  }
}
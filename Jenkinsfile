pipeline {
  agent any
  stages {
    stage('Compile') {
      steps {
        sh 'mvn clean install -Pprod -DskipTests'
        dir(path: './target/dist/tale') {
          sh 'cp tale-least.jar /home/workplace/Github/blueocean-plugin/blueocean/work/jobs/tale/branches/master/workspace/'
        }
        
      }
    }
  }
}
pipeline {
    agent any 
    stages {
    stage('maven install') {
      steps {
withMaven(maven: 'maven3.8.7') {
       sh 'mvn clean install'
}
      }
    }

  }
}

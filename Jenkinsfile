pipeline {
    agent any 
    stages {
    stage('maven install') {
      steps {
withMaven(maven: 'maven_3_8_7') {
       sh 'mvn clean install'
}
      }
    }

  }
}

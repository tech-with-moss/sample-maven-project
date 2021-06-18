pipeline {
    agent any 
    stages {
    stage('maven install') {
      steps {
 withMaven(maven: 'maven3') {
        sh 'mvn clean install'
}
      }
    }

  }
}

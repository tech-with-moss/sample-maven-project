pipeline {
  agent any
  
  stages {
    stage('maven install') {
      steps {
        echo 'Maven install initiating...'
        withMaven(globalMavenSettingsConfig: '', jdk: '', maven: '', mavenSettingsConfig: '', traceability: true) {
          sh 'mvn clean install'
        }
      }
    }
  }
}

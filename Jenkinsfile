pipeline {
    agent any 
    stages {
    stage('maven install') {
      steps {
 withMaven {
        sh 'mvn clean install'
}
      }
    }

  }
}

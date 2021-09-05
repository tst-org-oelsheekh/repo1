pipeline {
  agent { node { label 'jenkins-slaves' } }
  
  stages {
    stage('echo') {
      steps {
        sh 'echo hi from 1st repo from main branch release v2'
      }
    }
  }
}

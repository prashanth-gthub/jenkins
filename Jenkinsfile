pipeline {
agent any 
  stages {
    stage ('scm stage') {
      steps {
      git credentialsId: 'git_creds', url: 'https://github.com/prashanth-gthub/jenkins.git'
        
      }
    }
  }
}

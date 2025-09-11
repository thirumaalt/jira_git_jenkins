pipeline {
  agent any
  stages {
    stage('Hello Test') {
      steps {
        echo "Hello from Jenkins on branch: ${env.BRANCH_NAME}"
        sh 'ls -l'
      }
    }
  }
}

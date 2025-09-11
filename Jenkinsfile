pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        echo "Hello from Jenkins on branch: ${env.BRANCH_NAME}"
        sh 'ls -l'
      }
    }
  }
}

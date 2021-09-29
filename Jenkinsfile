pipeline {
  agent any
  stages {
    stage('test') {
      environment {
        DASHBOARD = 'BlueOcean'
      }
      steps {
        sh 'echo "Created Jenkinsfile from BlueOcean Dashboard"'
        sh 'echo "Environment: $DASHBOARD"'
      }
    }

    stage('List') {
      steps {
        sh 'ls -a'
      }
    }

  }
}
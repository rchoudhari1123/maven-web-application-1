pipeline {
  agent {
    node {
      label 'development'
    }

  }
  stages {
    stage('testing') {
      steps {
        sh 'echo "hi this is testing"'
      }
    }

  }
  environment {
    ocean_pipeline_testing = ''
  }
}
pipeline {
  agent any
  environment {
    NEW_VERSION = "1.0.1"
  }
  stages {
    stage('build') {
      steps {
        echo 'building code for my application'
        echo "building version ${NEW_VERSION}"
      }
    }

    stage('test') {
      steps {
        echo 'Unite Testing'
      }
    }

    stage('deploy') {
      steps {
        echo 'deploying to QA Env.'
      }
    }

  }
}

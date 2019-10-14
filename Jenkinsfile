pipeline {
  agent any

  }
  stages {
    stage('Checkout from CMS') {
      steps {
        echo 'Checkout from scm'
      }
    }
    stage('unit tests') {
      steps {
        echo 'unit tests'
      }
    }
    stage('static code analysis') {
      steps {
        echo 'static code analysis'
      }
    }
    stage('publiching artifacts') {
      steps {
        echo 'publiching artifacts'
      }
    }
    stage('deploy') {
      steps {
        echo 'deploy'
      }
    }
    stage('regression tests (optional)') {
      steps {
        echo 'regression tests (optional)'
      }
    }
    stage('integration tests (optional)') {
      steps {
        echo 'integration tests (optional)'
      }
    }
    stage('acceptance tests (optional)') {
      steps {
        echo 'acceptance tests (optional)'
      }
    }
    stage('jira ticket creation') {
      steps {
        echo 'jira ticket creation'
      }
    }
    stage('merge on testing') {
      steps {
        echo 'merge on testing'
      }
    }
  }
  environment {
    CI = 'true'
  }
}

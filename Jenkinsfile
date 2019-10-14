pipeline {
  agent {
    docker {
      image 'node:6-alpine'
      args '-p 3000:3000'
    }
    
  }
  stages {
    stage('Checkout from CMS') {
    
    }
    stage('unit tests') {
    
    }
    stage('static code analysis') {
    
    }
    stage('publiching artifacts') {
    
    }
    stage('deploy') {
    
    }
    stage('regression tests (optional)') {
    
    }
    stage('integration tests (optional)') {
    
    }
    stage('acceptance tests (optional)') {
    
    }
    stage('jira ticket creation') {
    
    }    
    stage('merge on testing') {
      steps {
        sh 'npm install'
      }
    }
    stage('Test') {
      steps {
        sh './jenkins/scripts/test.sh'
      }
    }
  }
  environment {
    CI = 'true'
  }
}

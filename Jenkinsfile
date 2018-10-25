pipeline {
  agent any
  stages {
    stage('Verify conflicts') {
      steps {
        echo 'ready to go'
      }
    }
    stage('Deliver Workspace') {
      steps {
        echo 'Workspace delivered'
      }
    }
    stage('Extract Workspace ') {
      steps {
        echo 'Extracted'
      }
    }
    stage('Transport to INT') {
      steps {
        echo 'Transported'
      }
    }
    stage('Import into INT') {
      steps {
        bat 'abc'
        echo 'imported'
      }
    }
    stage('END') {
      steps {
        echo 'Imported'
      }
    }
  }
}
pipeline {
  agent any
  stages {
    stage('Verify conflicts') {
      steps {
        echo 'ready to go'
        echo 'Start verification'
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
        echo 'imported'
      }
    }
    stage('Distribute SystemPreferences') {
      steps {
        echo 'Imported'
      }
    }
    stage('BA Review') {
      steps {
        echo 'approved'
        echo 'SAM: Status changed to "BA approval requried"'
      }
    }
  }
}
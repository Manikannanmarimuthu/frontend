pipeline {
  agent {
    label 'Workstation'
  }

  stages {
    stage('Compile/Build') {
      steps {
        echo 'compile'
      }
    }

    stage('Unit Tests') {
      steps {
        echo 'unit tests'
      }
    }

    stage('Quality Control') {
      steps {
        echo 'Quality Control'
      }
    }

   stage('Upload Code to centralized Places') {
      steps {
        echo 'Upload'
      }
    }
  }

}
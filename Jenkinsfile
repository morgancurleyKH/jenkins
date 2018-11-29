pipeline {
  agent any
  stages {
    stage('Clone') {
      steps {
        sh 'echo "Cloning"'
      }
    }
    stage('Analyze') {
      steps {
        sh 'echo "Analyzing"'
        echo 'WooHoo'
      }
    }
    stage('Build') {
      steps {
        sh 'echo "Building"'
      }
    }
    stage('Deploy') {
      steps {
        sh 'echo "Deploying"'
      }
    }
    stage('Done') {
      steps {
        echo 'Finis'
      }
    }
  }
}
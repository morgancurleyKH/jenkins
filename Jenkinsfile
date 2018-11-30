pipeline {
    // agent {
    //   docker { image 'node:7-alpine' }
    // }
  agent any
  stages {
    stage('Clone') {
      steps {
        sh 'echo "Cloning"'
        sh 'echo `which docker`'
        sh 'echo $PATH'
        sh 'node --version'
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

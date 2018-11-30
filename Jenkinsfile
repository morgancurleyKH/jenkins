pipeline {
    // agent {
    //   docker { image 'node:7-alpine' }
    // }
    stages {
    stage('Clone') {
      steps {
        sh 'echo "Cloning"'
        sh 'which docker'
        sh 'echo $PATH'
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
        sh 'node --version'
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

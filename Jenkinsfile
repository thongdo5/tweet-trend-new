pipeline {
  agent {
    node {
      label 'maven'
    }
  }

  stages {
    stage('Clone-code') {
      steps {
        git branch: 'main', url: 'https://github.com/thongdo5/tweet-trend-new.git'
      }
    }
  }
}
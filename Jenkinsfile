pipeline {
  agent {
  label 'master'
  }
  stages {
    stage("foo") {
      steps {
            sh 'echo "The answer is 42"'
      }
    }
    stage("bar") {
      steps {
       sh "echo bar"
      }
    }
  }
  }

pipeline {
  agent any
  stages {
    stage('Greeting') {
      steps {
        echo 'Hello!'
      }
    }

    stage('End') {
      agent any
      steps {
        echo 'Good Bye my friend!'
      }
    }

  }
}
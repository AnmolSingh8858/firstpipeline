pipeline {
  agent any
  stages {
    stage('Fetch code') {
      steps {
        git(url: 'https://github.com/AnmolSingh8858/firstpipeline.git', branch: 'main', poll: true)
      }
    }

    stage('build') {
      steps {
        sh 'sudo apt install apache2 y'
      }
    }

    stage('deploy') {
      steps {
        sh 'echo "hello"'
      }
    }

  }
}
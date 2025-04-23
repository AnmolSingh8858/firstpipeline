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
        sh 'sudo apt-get install jenkins'
      }
    }

    stage('deploy') {
      steps {
        sh 'echo "hello"'
      }
    }

  }
}
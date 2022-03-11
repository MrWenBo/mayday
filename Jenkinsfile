pipeline {
  agent any
  stages {
    stage('1') {
      steps {
        echo '1'
      }
    }

    stage('') {
      steps {
        git(url: 'https://github.com/MrWenBo/mayday.git', branch: 'dev', changelog: true, credentialsId: '54494c2c-fd86-4753-a61e-26b3bd1be022', poll: true)
      }
    }

  }
}
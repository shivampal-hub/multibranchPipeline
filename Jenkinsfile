pipeline {

  agent any
  stages {

    stage('Hello') {

      steps {

        sh '''

          java -version

        '''

      }

    }
    stage('cat README') {

      when {

        branch "fix-*"

      }

      steps {

        sh '''

          cat README.md

        '''

      }

    }

  }
}

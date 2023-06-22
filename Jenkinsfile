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

      /*when {

        branch "feature-*"

      }*/

      steps {

        sh '''

          cat README.md

        '''

      }

    }

  }
}

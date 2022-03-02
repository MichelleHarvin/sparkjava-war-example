pipeline {
    agent {label 'michelle'}
  stages {
    stage('build') {
      steps {
          sh '''
          echo "Do something"
          pwd
          uname
      }
    }
    stage ('test') {
      steps { 
         echo "Do something"
      }
    }
    stage('deploy') {
      steps{
          echo "Do something"
      }
    }
  }
}

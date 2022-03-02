pipeline {
    agent {label 'michelle'}
  stages {
    stage('build') {
      steps {
          sh '''
          echo "Do something"
          pwd
          uname
          docker ps
          echo "Do something"
          mvn clean install
          '''
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

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
          sh '''
           docker cp /root/workspace/Michelle_Harvin/Michelle_Harvi/target/sparkjava-hello-world-1.0.war tomcat://usr/local/tomcat/webapps
          '''
      }
    }
  }
}

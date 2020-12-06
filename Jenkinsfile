pipeline {
   agent any

   stages {
      stage('Build') {
         steps {
           sh './jenkins/build.sh'
         }
      }
      stage('testing') {
         steps {
            sh 'sonar-scanner  -Dsonar.projectKey=angular  -Dsonar.sources=.  -Dsonar.host.url=http://192.168.0.109:9000  -Dsonar.login=518d11b95dd7bff5d2fe49ec785e30bac18f9808'
         }
      }
      stage('Production deploye') {
         steps {
            sh 'date'
         }
      }
   }
}


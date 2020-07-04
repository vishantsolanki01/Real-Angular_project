pipeline {
   agent any

   stages {
      stage('Build') {
         steps {
           sh ''./jenkins/build.sh''
         }
      }
      stage('testing') {
         steps {
            sh 'pwd'
         }
      }
      stage('Production deploye') {
         steps {
            sh 'date'
         }
      }
   }
}


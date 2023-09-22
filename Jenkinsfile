pipeline {
     agent any
     stages {
         stage('build') {
              when {
                  branch 'master'             
              }
              steps {
                 git 'https://github.com/pitcheripraveen/praveen-simple-java-maven-app.git'
              }
         }
         stage('code is verifed or not') {
             steps{
                 echo " code is pushed from the master branch"
             }
         }
     }
}

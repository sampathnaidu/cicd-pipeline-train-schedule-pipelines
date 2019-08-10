pipeline {
 
  agent any
   stages {
    stage ('Build') {
     steps{
     echo 'Runnig build automation'
     sh './gradlew build --no-daemon'
     archiveArtifacts artifatcs: 'dist/trainSchedule.zip'
     
         }
       }
     }
   }

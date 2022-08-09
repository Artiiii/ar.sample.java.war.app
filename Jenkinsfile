@Library('shared-library') _
pipeline {
    agent any
    stages {
    
       stage('Maven Build') {
           tools {
                   jdk "java"
                }
           steps {
               BuildApp()               
           }
           }
          stage('Sonar Analysis') {
           tools {
                   jdk "java"
                }
           steps {
               SonarApp()               
           }
           }
         
        stage('Store war file in Nexus') {
           tools {
                   jdk "java"
                }
           steps {
               StoreToNexus()               
           }
           } 
         stage('Deploy App') {
           tools {
                   jdk "java"
                }
           steps {
               DeployApp()               
           }
           }
    
    }
}


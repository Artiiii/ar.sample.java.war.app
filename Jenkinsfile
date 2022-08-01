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
        stage('Store war file in Nexus') {
           tools {
                   jdk "java"
                }
           steps {
               StoreToNexus()               
           }
           }
       stage('Deploy App') {
           steps {           
               DeployApp()
           }
           }   
    
    }
}


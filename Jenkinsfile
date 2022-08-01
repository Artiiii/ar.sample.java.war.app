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
       stage('Deploy App') {
           steps {           
               DeployApp()
           }
           }   
    
    }
}


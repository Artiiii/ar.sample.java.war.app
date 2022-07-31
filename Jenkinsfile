@Library('shared-library') _
pipeline {
    agent any
    stages {
    
       stage('Maven Build') {
           steps {
               BuildApp()               
           }
           }
        stage('Sonar Analysis') {
           steps {
               SonarApp()               
           }
        
       stage('Deploy App') {
           steps {           
               DeployApp()
           }
           }   
    
    }
}  
//

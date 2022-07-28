@Library('shared-library') _
pipeline {
    agent any
    stages {
    
       stage('Maven Build') {
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
//

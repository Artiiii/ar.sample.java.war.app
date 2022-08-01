@Library('shared-library') _
pipeline {
    agent any
    stages {
    
       stage('Maven Build') {
           tools {
                   jdk "jdk-11.0.16"
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


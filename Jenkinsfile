@Library('shared-library') _
//Mavenbuild 'https://github.com/Artiiii/ar.sample.java.war.app.git'
pipeline {
    agent any
    stages {
 //       stage('Git Checkout') {
 //           steps {
 //             GitCheckout(
 //               branch: "main",
 //               url: "https://github.com/Artiiii/ar.sample.java.war.app.git"
 //               //hello("Arti")
 //                 )
 //           
 //           }
 //       }
 //       stage('Maven Build') {
 //           steps {
 //               BuildApp()               
 //           }
 //           }
 //       stage('Deploy App') {
 //           steps {           
 //               DeployApp()
 //           }
 //           }
        stage('Restart Tomcat') {
            steps {           
                RestartTomcat()
            }
            }
            
    
    }
}


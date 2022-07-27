@Library('shared-library') _
//Mavenbuild 'https://github.com/Artiiii/ar.sample.java.war.app.git'
pipeline {
    agent any
    stages {
        stage('Git Checkout') {
            steps {
              BuildJava(
                branch: "main",
                url: "https://github.com/Artiiii/ar.sample.java.war.app.git"
                //hello("Arti")
                  )
            
            }
        }
        stage('Maven Build') {
            steps {
                "H:\apache-maven-3.8.6-bin\apache-maven-3.8.6\bin\mvn.exe" clean package
                //BuildApp()
            }
            }
            
    
    }
}

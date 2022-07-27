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
                 //bat label: '', script: 'mvn clean package'
                BuildApp()
                //sh "mvn clean package"
            }
            }
            
    
    }
}
C:\Users\Arti Pal\Documents\tools\apache-tomcat-10.0.23-windows-x64\apache-tomcat-10.0.23\webapps

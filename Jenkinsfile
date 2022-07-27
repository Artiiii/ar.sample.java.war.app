@Library('shared_library')_
//jenkinsForJava 'https://github.com/Artiiii/ar.sample.java.war.app.git'
pipeline {
    agent any
    stages {
        stage('Git Checkout') {
            steps {
            Build (
                branch: "main",
                url: "https://github.com/Artiiii/ar.sample.java.war.app.git"
            )
            }
    }
    }
}

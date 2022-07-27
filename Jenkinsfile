@Library('shared_library@main')_
//jenkinsForJava 'https://github.com/Artiiii/ar.sample.java.war.app.git'
pipeline {
    agent any
    stages {
        stage('Git Checkout') {
            steps {
            BuildJava(
                branch: "main",
                url: "https://github.com/Artiiii/ar.sample.java.war.app.git"
            )
            }
    }
    }
}

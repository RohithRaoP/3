pipeline {
    agent any

    tools {
        jdk 'jdk17'
        maven 'M3'
    }

    stages {
        stage('Build & test') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}





pipeline {
    agent any

    tools {
        jdk 'java'
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





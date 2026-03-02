pipeline {
    agent {
        docker {
                 image 'maven:3.9.6-eclipse-temurin-17'
            }
    }

    stages {
        stage('Build & test') {
            steps {
                sh 'mvn clean package'
            }
        }
stage('Docker Build') {
    steps {
        sh 'docker build -t rohith/ecommerce-app .'
           } 
      }
    }
 }





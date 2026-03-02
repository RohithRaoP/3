pipeline {
    agent any
    stages {
        stage('Build & test') {
            steps {
                sh 'mvn clean package'
            }
        }
stage('Docker Build Image') {
    steps {
        sh 'docker build -t rohith/ecommerce-app .'
           } 
      }
    }
 }





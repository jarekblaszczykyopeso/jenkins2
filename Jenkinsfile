pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying'
            }
        }
    }
    post {
       always{
         mail to: ‘jaroslaw.blaszczyk@yopeso.com’, subject “test sub”’, body “test body”        
         }
    }      
}
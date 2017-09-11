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
    always {
        mail to: 'team@example.com',
             subject: "Failed Pipeline”,
             body: "Something is . . . "
    }     
}
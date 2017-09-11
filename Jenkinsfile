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
            echo "Cos"
            //doesnt work mai, maybe because of authenitcation issues
            //mail body: 'body only', subject: 'Subject only', to: 'jaroslaw.blaszczyk@yopeso.com'
        }
    }
}
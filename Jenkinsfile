
pipeline {

    agent any

    stages {

        stage("build") {
            steps {
                sh 'npm install'
            }
            steps {
                sh 'npm start'
            }
        }

        stage("test") {
            steps {
                sh 'npm run test'
            }
        }

        stage("deploy") {
            steps {
                echo 'Deploying application ...'
            }
        }
    }

}


pipeline {
    agent any
    tools {
        nodejs '18.12.1'
    }
    stages {
        stage("build") {
            steps {
                sh 'npm install'
            }
        }
        stage("test") {
            steps {
                sh 'npm start'
            }
        }
        stage("deploy") {
            steps {
                echo 'Deploying application ...'
            }
        }
    }

}

# go-webapp-sample



## Preface
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build the job'
            }
        }
        stage('Test') {
            steps {
                echo 'Test the job'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy the job'
            }
        }
    }
}

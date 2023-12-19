pipeline {
    //agent any
    agent { node { label 'workstation' } }
    environment {
           url = "google.com"
        }

    stages {
        stage('build') {
            steps {
                echo url

            }
        }
        stage('test') {
            steps {
                echo 'Hello World'
            }
        }
        stage('code quality') {
            steps {
                echo 'Hello World'
            }
        }
        stage('code security') {
            steps {
                echo 'Hello World'
            }
        }
         stage('app deploy') {
                    steps {
                        echo 'Hello World'
                    }
                }
    }
}

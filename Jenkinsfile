pipeline {
    //agent any
    agent { node { label 'workstation' } }
    environment {
           url = "google.com"
           ssh_key= credentials('centos-ssh')
        }

    stages {
        stage('build') {
            steps {
                echo url
                echo ssh_key

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

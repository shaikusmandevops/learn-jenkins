pipeline {
    //agent any
    agent { node { label 'workstation' } }
    environment {
           url = "google.com"
           ssh_key= credentials('centos-ssh')
        }
        options {
                ansiColor('xterm')
                }

    stages {
        stage('build') {
            steps {
                echo url
                echo ssh_key
                sh 'env'
                sh 'ansible -i 52.87.217.141, all -e ansible_user=${SSH_USER} -e ansible_password=${SSH_PSW} -m ping'

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

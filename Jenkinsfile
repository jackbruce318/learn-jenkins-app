pipeline {
    agent any

    stages {
        stage('w/o Docker') {
            steps {
                sh '''
                    echo "Without Docker"
                    ls -la
                    touch container-no.txt
                '''
            }
        }
    }
}

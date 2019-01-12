pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello New World"'
                sh '''
                    echo "Multiline shell steps works too - mamy times!"
                    ls -lah
                '''
            }
        }
    }
}

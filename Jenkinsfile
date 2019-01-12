pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello New World and Mars"'
                sh '''
                    echo "Multi-line shell steps works too - mamy multiple times!"
                    ls -lah
                '''
            }
        }
    }
}

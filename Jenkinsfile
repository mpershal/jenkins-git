pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello New New World - planet or what!!!"'
                sh '''
                    echo "Multi-line shell steps works too - so many times!"
                    ls -lah
                '''
            }
        }
    }
}

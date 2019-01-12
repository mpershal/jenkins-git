pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello New World!!!"'
                sh '''
                    echo "Multi-line shell steps works too - mult times!"
                    ls -lah
                '''
            }
        }
    }
}

pipeline {
    agent any
    stages {
        stage('Deploy') {
            steps {
                sh 'echo "Hello, this is a feature branch"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}

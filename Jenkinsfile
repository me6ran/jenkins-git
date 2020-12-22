pipeline {
    agent any
    stages {
        stage('Deploy') {
            steps {
                sh 'echo "Hello, this is a bug fixed"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}

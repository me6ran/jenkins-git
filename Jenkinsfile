pipeline {
    agent any
    stages {
        stage('Deploy') {
            steps {
                sh 'echo "Hello, this is a feature branch"'
                script {
                    def msg = 2 > 1 ? 'it is bigger':'it is smaller'
                    echo msg
                }
            }
        }
    }
}

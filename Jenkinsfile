
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
    post {
        always {
            mail body: 'Test', from: '', subject: 'Test123', to: 'kodatisuresh@gmail.com'
        }
    }
}


pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World; Testing With git commit'
            }
        }
    }
    post {
        always {
            mail body: 'Test', from: '', subject: 'Test123', to: 'kodatisuresh@gmail.com'
        }
    }
}

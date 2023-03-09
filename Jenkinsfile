pipeline {
    agent any
    stages {
        stage('echo') {
            steps {
                sh 'echo "Hello"'
            }
        }
        stage('git version') {
            steps {
                sh 'git --version'
            }
        }
    }
}

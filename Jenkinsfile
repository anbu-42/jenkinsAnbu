pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/yourusername/yourrepo.git'
            }
        }
        stage('Run Python Script') {
            steps {
                sh 'python3 hello.py'
            }
        }
    }
}

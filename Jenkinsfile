pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
               git branch: 'main', url: 'https://github.com/anbu-42/jenkinsAnbu.git'
            }
        }
        stage('Run Python Script') {
            steps {
                bat 'C:\Users\Eraiyanbu\AppData\Local\Programs\Python\Python310\python.exe demo.py'
            }
        }
    }
}

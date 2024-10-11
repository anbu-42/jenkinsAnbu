pipeline {
    agent any
     // environment {
     // env.PATH = env.PATH + "c:\\Windows\\System32"
 // }
    stages {
        stage('Clone Repository') {
            steps {
               git branch: 'main', url: 'https://github.com/anbu-42/jenkinsAnbu.git'
            }
        }
        stage('Check Environment') {
            steps {
                bat 'echo %PATH%'
                bat 'python --version'
            }
        }
        stage('Run Python Script') {
            steps {
                bat 'python demo.py'
            }
        }
    }
}

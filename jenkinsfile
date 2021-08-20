pipeline {
    agent any

    stages {
        stage('----clean-------') {
            steps {
                echo 'clean..'
                sh "mvn clean"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                sh "mvn Test"
            }
        }
        stage('-------package--------') {
            steps {
                echo 'packages....'
                sh "packages............................mvn"
            }
        }
    }
}

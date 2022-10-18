pipeline {
    agent any

    stages {
        stage('Git Pull - 1') {
            steps {
                echo 'pulling from github...'
            }
        }
        stage('Hello - 2') {
            steps {
                echo 'Hello World'
            }
        }
        stage('UAT - 3') {
            steps {
                echo 'pre Prod'
            }
        }
        stage('Deploy - 4') {
            steps {
                echo 'Hello World!'
            }
        }
    }
}

pipeline {
    agent any

    stages {
        stage('Git Pull') {
            steps {
                echo 'pulling from github...'
            }
        }
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('UAT') {
            steps {
                echo 'pre Prod'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Hello World!'
            }
        }
    }
}

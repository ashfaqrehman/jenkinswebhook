pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Building build number: ${env.BUILD_ID}.."
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}

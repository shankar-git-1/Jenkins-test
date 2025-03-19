pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                echo 'Hello from Jenkins Pipeline!'
                sh 'echo "Current branch: $GIT_BRANCH"'
            }
        }
    }
}

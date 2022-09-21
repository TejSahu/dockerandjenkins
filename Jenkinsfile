pipeline {
    agent any

    stages{
        stage('Verify Branch'){
            steps{
                echo "$GIT_BRANCH"
            }
        }

        stage('Docker commands'){
            steps{
                sh 'echo "Hello World'
                sh 'docker images'
            }
        }
    }
}
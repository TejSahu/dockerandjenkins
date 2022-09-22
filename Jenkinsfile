pipeline {
    agent {label 'JenkinsNode'}

    stages{
        stage('Verify Branch'){
            steps{
                echo "$GIT_BRANCH"
            }
        }

        stage('Docker commands'){
            steps{
                sh 'echo "Hello World"'
                sh 'docker images'
                sh 'docker ps -a'
            }
        }
    }
}
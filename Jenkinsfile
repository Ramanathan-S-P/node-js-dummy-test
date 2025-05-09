pipeline {
    agent any

    triggers {
        githubPush()
    }

    stages {
        stage('Greet') {
            steps {
                echo "Hello! A new push was made to the Git repository."
            }
        }
    }
}

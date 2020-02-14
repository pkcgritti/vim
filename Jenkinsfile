pipeline {
    agent any

    environment {
        PROJECT_NAME = "vim"
    }

    stages {
        stage("Pre-build") {
            steps {
                echo "Pre-building application"
                echo "${GIT_BRANCH}"
            }
        }
    }
}

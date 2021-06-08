
pipeline {
    agent {
        node {
        label 'master'
        customWorkspace env.BRANCH
        }
    }
    stages {

        stage('Test') {
            steps {
                echo 'Hi from dev ...'
            }
        }

    }
}

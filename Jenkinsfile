pipeline {
    agent any
    stages {
        stage('building master bracnh') {
            when {
                tag "release-*"
            }
            steps {
                echo 'building with tag by me'
            }
        }
    }
}

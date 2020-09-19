pipeline {
    agent any
    stages {
        stage('building master bracnh') {
            when {
                tag "2.0"
            }
            steps {
                echo 'building with tag by me'
            }
        }
    }
}

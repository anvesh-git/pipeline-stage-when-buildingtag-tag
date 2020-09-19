pipeline {
    agent any
    stages {
        stage('building master bracnh') {
            when {
                buildingTag()
            }
            steps {
                echo 'building with tag by me'
            }
        }
    }
}

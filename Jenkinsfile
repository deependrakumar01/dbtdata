pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello' 
                cd NewFolder
                sh "cd /NewFolder/test.sh World"
            }
        }
    }
}

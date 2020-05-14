pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                sh '''
                    echo 'Hello'
                    'cd /Users/saumyamathur/Applications/jenkins/'
                    sh '. test.sh World'
                '''
            }
        }
    }
}

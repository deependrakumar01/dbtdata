pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                dir('/Users/saumyamathur/Applications/jenkins/'){
                    echo `pwd`
                    sh  '. test.sh World'
                    }               
                    echo "Hello"
            }
        }
    }
}

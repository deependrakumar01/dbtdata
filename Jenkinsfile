pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                dir('/Users/saumyamathur/Applications/jenkins/'){
                    
                    sh  '. test.sh World'
                    sh 'pwd'
                    sh 'cd $home'
                    sh 'echo : pwd'
                    
                    }               
                    echo "Hello"
            }
        }
    }
}

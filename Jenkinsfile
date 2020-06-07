pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                dir('/Users/saumyamathur/Applications/jenkins/'){
                    
                    sh  '. test.sh World'
                    sh 'pwd'
                    sh 'cd /Users/saumyamathur'
                    sh 'pwd'
                    
                    }               
                    echo "Hello"
            }
        }
        
         stage('Stage 2') {
            steps {
                dir('/Users/saumyamathur/Applications/jenkins/'){
                    
                    sh  '. test.sh World'
                    sh 'pwd'
                    sh 'cd /Users/saumyamathur'
                    sh 'pwd'
                    
                    }               
                    echo "Hello"
            }
        }
    }
}

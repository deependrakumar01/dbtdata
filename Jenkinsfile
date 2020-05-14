pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                dir('/Users/saumyamathur/Applications/jenkins/'){
                    
                    sh  '. test.sh World'
                    sh '''
                    echo path is: `pwd`
                    }               
                    echo "Hello"
            }
        }
    }
}

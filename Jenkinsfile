pipeline {
    agent any
       stages{
        stage('git-checkout') {
            agent any
            steps {
                git branch: 'master', url: 'https://github.com/web3j/sample-project-maven.git'
            }
        }
        stage('Git-Release') {
            steps {
                echo "Git-Release = v1.0.${env.BUILD_TAG}"
            }
        }   
        
    }
} 

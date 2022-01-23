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
                echo "Git-Release = v1.0.${env.BUILD_NUMBER}"
                echo "Git-Release = ${env.BUILD_TAG}"
                echo "Git-Release = ${env.EXECUTOR_NUMBER}"
                echo "Git-Release = ${env.NODE_NAME}"
                echo "Git-Release = ${env.NODE_LABELS}"
                echo "Git-Release = ${env.WORKSPACE}"
                echo "Git-Release = ${env.JENKINS_HOME}"
                echo "Git-Release = ${env.JENKINS_URL}"
                echo "Git-Release = ${env.BUILD_URL}"
                echo "Git-Release = ${env.JOB_URL}"
                
            }
        }   
        
    }
} 

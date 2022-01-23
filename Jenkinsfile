pipeline {
    agent any
       stages{
        stage('git-checkout') {
            agent any
            steps {
                git branch: 'master', url: 'https://github.com/web3j/sample-project-maven.git'
            }
        }
        stage('Env-performnce-check') {
            steps {
                echo "BUILD_NUMBER = v1.0.${env.BUILD_NUMBER}"
                echo "BUILD_TAG = ${env.BUILD_TAG}"
                echo "EXECUTOR_NUMBER = ${env.EXECUTOR_NUMBER}"
                echo "NODE_NAME = ${env.NODE_NAME}"
                echo "NODE_LABELS = ${env.NODE_LABELS}"
                echo "WORKSPACE = ${env.WORKSPACE}"
                echo "JENKINS_HOME = ${env.JENKINS_HOME}"
                echo "JENKINS_URL = ${env.JENKINS_URL}"
                echo "BUILD_URL = ${env.BUILD_URL}"
                echo "JOB_URL = ${env.JOB_URL}"
                echo "P4_CLIENT = ${env.P4_CLIENT}"
                echo "P4_CHANGELIST = ${env.P4_CHANGELIST}"
                echo "P4_PORT = ${env.P4_PORT}"
                echo "P4_ROOT = ${env.P4_ROOT}"
                echo "P4_USER = ${env.P4_USER}"
                echo "P4_TICKET = ${env.P4_TICKET}"
                echo "P4_REVIEW  = ${env.P4_REVIEW }"
                echo "P4_REVIEW_TYPE  = ${env.P4_REVIEW_TYPE }"
            }
        }   
        
    }
} 

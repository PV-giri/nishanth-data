pipeline {
    agent any
    stages{
        stage('git-checkout') {
            agent any
            steps {
                git branch: 'master', url: 'https://github.com/PV-giri/nishanth-data.git'
            }
        }
        stage('list-objects') {
            agent any
            steps {
                sh '''#!/bin/bash
            
                    ls -ltrt
                    pwd
                '''
            }
         }
    }
}

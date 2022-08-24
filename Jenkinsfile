pipeline {
    agent any
    stages {
        stage('Running sh scripts') {
            steps {
                sh '''
                bash ./jenkins.sh
                bash ./jenkins2.sh
              
              '''
            }
        }

    }
}

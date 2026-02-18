pipeline {
    agent any

    stages {
        stage ('checkout') {
            steps {
                git branch: 'master' , url : 'https://github.com/bmanisha04/mission.git'
            }
        }

        stage('build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
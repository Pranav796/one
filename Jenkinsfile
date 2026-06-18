pipeline {
    agent any

    tools {
        maven 'Maven'
    }

    stages {
        stage('Build WAR') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}

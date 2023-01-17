pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/dawodu98/angular-google-maps.git']]])
            }
        }
        stage('git') {
            steps {
                git 'https://github.com/dawodu98/angular-google-maps.git'
            }
        }
        stage('timestamps') {
            steps {
                timestamps {
    // some block
}
            }
        }
        stage('Hello') {
            steps {
                echo 'babatunde'
            }
        }
        stage('catchError') {
            steps {
                catchError(message: 'pass') {
    // some block
}
            }
        }
    }
}

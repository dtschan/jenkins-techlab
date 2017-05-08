pipeline {
    agent any
    options {
        buildDiscarder(logRotator(numToKeepStr: '1'))
        timeout(time: 5, unit: 'MINUTES')
        timestamps()
    }
    stages {
        stage('Greeting') {
            steps {
                echo 'Hello, World!'
            }
        }
    }
}

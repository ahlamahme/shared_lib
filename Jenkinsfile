// Jenkinsfile

@Library('my-shared-library') _

pipeline {
    agent any
    
    stages {
        stage('Example') {
            steps {
                // Call the function from the shared library
                hello 'Jenkins'
            }
        }
    }
}

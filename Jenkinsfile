/* Requires the Docker Pipeline plugin */
pipeline {
    agent any
    stages {
         stage('build') {
            steps {
                echo 'build the application...'
                echo 'application built'
            }
         }
         stage('test') {
            steps {
                echo 'testing the application...'
            }
         }
         stage('deploy') {
            steps {
                echo 'deploying the application...'
            }
         }
    }
}

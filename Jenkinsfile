@Library('jenkins-shared-libraries@main') _

pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                script {
                    build() // Call the common function
                }
            }
        }
    }
}

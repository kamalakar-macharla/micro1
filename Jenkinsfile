@Library('jenkins-shared-libraries') _

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

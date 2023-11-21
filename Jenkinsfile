@Library('jenkins-shared-libraries@main') _

node {
    stage('Build') {
        try {
            //build() // Call the common function
            echo "Build is running..."
            bat'''
              dir
            '''
        } catch (Exception e) {
            currentBuild.result = 'FAILURE'
            throw e
        }
    }
}


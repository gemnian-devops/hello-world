pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo "Build name is ${currentBuild.displayName}"
            }
            post {
                success {
                    script {
                        currentBuild.result = 'FAILURE'
        }
    }
}
         }

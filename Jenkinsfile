pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello world!"'
                currentBuild.rawBuild.project.setDescription = "testing purpose"               
            }
        }
    }
}

pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello world!"'
                sh '''def a = "${currentBuild.description}"
                echo "${a}"'''
               
               
            }
        }
    }
}

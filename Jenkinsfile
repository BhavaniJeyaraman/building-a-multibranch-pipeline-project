pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello world!"'
                def a = "${currentBuild.description}"
                sh 'echo "${a}"'
               
               
            }
        }
    }
}

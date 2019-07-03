pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello world!"'
                //currentBuild.rawBuild.project.setDescription = "testing purpose"               
                item = jenkins.instance.getItemByFullName("akmid")
                item.setDescription("testing purpose")
                item.save()
            }
        }
    }
}

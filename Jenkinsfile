pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello world!"'
                sh '''currentBuild.description = "testing purpose"'''              
                //item = jenkins.instance.getItemByFullName("akmid")
                //item.setDescription("testing purpose")
                //item.save()
            }
        }
    }
}

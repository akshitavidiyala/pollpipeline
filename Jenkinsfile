pipeline {
    agent any

    triggers {
        pollSCM('H/1 * * * *')
    }

    stages {
        stage('Build') {
            steps {
                echo "Pipeline triggered by Poll SCM!"
                sh "ls -l"
            }
        }
    }
}



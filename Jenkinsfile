pipeline {
    agent any
    stages {
        stage('TryMultiBranch') {
            steps {
                pwd()
                sh 'echo check_file_content'
                sh 'cat Lfile0329.java'
            }
        }
    }
}

pipeline {
    agent any

    stages {
        stage('Create Folder') {
            steps {
                script {
                    def folderPath = "/tmp/my-folder" // change path for Windows
                   bat 'mkdir C:\\JenkinsFolder'
                                       echo "Folder created at ${folderPath}"
                }
            }
        }
    }
}

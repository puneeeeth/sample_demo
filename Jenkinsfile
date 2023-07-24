pipeline {
    agent any
    stages {
        stage ('Discover') {
            steps {
                echo "Discoverd the step successfully"
                bat 'Sample.bat'
            }
        }
        stage ('Pull') {
            steps {
                echo "Pull the discoverd stage file"
                bat 'Sample.bat'
            }
        }
    }
}

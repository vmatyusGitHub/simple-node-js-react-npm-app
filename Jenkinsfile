pipeline {
    agent {
        docker {
            image 'node:6-alpine'
            args '-p 3000:3000'
        }
    }
    stages {
        stage('Build') {
            steps {
                def username = 'Jenkins'
                echo 'Hello Mr. ${username}'
                echo "I said, Hello Mr. ${username}"
            }
        }
    }
}

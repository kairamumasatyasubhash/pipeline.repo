
pipeline {
    aget any
    stages {
        stage ('DockerBuildPush') {
            steps {
                sh "Docker pull nginx"
                echo "******* Print the images*******"
                sh  "Docker images"
            }
        }
    }
}

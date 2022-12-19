pipeline {
    
    agent any
    
    stages {
        stage("build") {
            steps {
                echo "building the application..."
                withMaven(maven: '3.8.6') {
                    sh "mvn clean install"
                }
            }
        }
    }
}

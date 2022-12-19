pipeline {
    
    agent any
    
    stages {
        stage("build") {
            steps {
                echo "building the application..."
                withMaven(maven: 'Maven-3.8.6') {
                    sh "mvn clean install"
                }
            }
        }
    }
}

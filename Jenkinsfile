pipeline {
    
    agent any
    
    stages {
        stage("build") {
            steps {
                echo "building the application..."
                withMaven(maven: 'maven-latest') {
                    sh "mvn clean install"
                }
            }
        }
    }
}

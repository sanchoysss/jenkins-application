pipeline {
    
    agent any
    
    stages {
        stage("build") {
            steps {
                echo "building the application..."
                maven(maven : 'Maven_3.8.6') {
                    sh "mvn clean install"
                }
            }
        }
    }
}

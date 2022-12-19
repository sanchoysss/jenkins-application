pipeline {
    
    agent any
    
    stages {
        stage("build") {
            steps {
                echo "building the application..."
                withMaven {
                    sh "mvn clean install"
                }
            }
        }
    }
}

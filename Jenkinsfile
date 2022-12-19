pipeline {
    
    agent any
    
    stages {
        stage("build") {
            steps {
                echo "building the application..."
                sh '''
                                    echo "PATH = ${PATH}"
                                    echo "M2_HOME = ${M2_HOME}"
                                '''
                sh 'mvn install'
            }
        }
    }
}

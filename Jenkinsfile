pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sudo sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}

pipeline {
    agent any
    stages {
        stage('---clean---') {
            steps {
                sh "/usr/local/maven/bin/mvn clean"
            }
        }
        stage('--test--') {
            steps {
                sh "/usr/local/maven/bin/mvn test"
            }
        }
        stage('--package--') {
            steps {
                sh "/usr/local/maven/bin/mvn package"
            }
        }
    }
}

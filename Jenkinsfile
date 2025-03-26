pipeline {
    agent any
    stages {
        stage("Build") {
            steps {
                sh 'mvn -DskipTests clean pachage'
            }
        }
        stage("Test") {
            steps {
                sh 'mvn test'
            }
        }
    }
}

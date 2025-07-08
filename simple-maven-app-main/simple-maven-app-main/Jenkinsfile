pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Simulating: git checkout'
            }
        }

        stage('Build') {
            steps {
                echo 'Simulating: mvn clean package'
            }
        }

        stage('Test') {
            steps {
                echo 'Simulating: mvn test'
                echo 'Simulating: publishing JUnit test results'
            }
        }

        stage('SonarQube Analysis') {
            steps {
                echo 'Simulating: SonarQube analysis with mvn sonar:sonar'
            }
        }

        stage('Archive') {
            steps {
                echo 'Simulating: archiving artifacts (target/*.war)'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Simulating: SCP deploy of WAR file to remote server'
            }
        }
    }
}

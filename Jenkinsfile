pipeline {
    agent any
    tools {
        jdk 'JDK11'
    }
    stages {
        stage('build') {
            steps {
                echo 'Build started'
                bat 'mvn --version'
                bat 'mvn clean compile'
                echo 'Build Testing finished successfully'
                bat 'mvn package venu'
                echo 'Build Finished Succesfully'
            }
        }
    }
}
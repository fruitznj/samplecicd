pipeline {

    agent any

    stages {

        stage ('Build') {
            steps {
                withMaven(maven: 'maven-3.9.2') {
                    sh 'mvn clean package'
                }
           
            }

        }

    }

}

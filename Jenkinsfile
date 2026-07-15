pipeline {

    agent any

    stages {

        stage('Compile') {

            steps {

                bat 'javac ia.java'

            }

        }

        stage('Run') {

            steps {

                bat 'java ia'

            }

        }

    }
}

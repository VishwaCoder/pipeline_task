pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                javac BubbleSort.java
            }
        }
        stage('Run') {
            steps {
                java BubbleSort
            }
        }
    }
}

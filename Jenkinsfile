pipeline {
    agent {
        node {
            label 'ubuntuVM'
			}
    }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
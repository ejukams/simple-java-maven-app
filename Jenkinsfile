pipeline {
    agent {
        node {
            label 'ubuntuVM'
			}
    }
    stages {
        stage('Build-app') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
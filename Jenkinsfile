pipeline {
    agent {
        node {
            label 'DT00405'
			//label 'ubuntuVM'
			}
    }
    stages {
        stage('Build-app') { 
            steps {
                //sh 'mvn -B -DskipTests clean package' 
				bat 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
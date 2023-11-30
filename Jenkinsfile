pipeline {
    agent none // Kein Agent hier, weil später spezifischer Agent zugewiesen wird

    stages {
        stage('Stage 1') {
            agent { label 'my-ec2-agent' }  // Hier wird der spezifische Agent zugewiesen
                echo 'Ausführung der Stage 1'
            }
        }
        stage('Stage 2') {
            agent { label 'my-ec2-agent' }  // Hier wird der spezifische Agent zugewiesen
            steps {
                echo 'Ausführung der Stage 2'
            }
        }
        stage('Stage 3') {
            agent { label 'my-ec2-agent' }  // Hier wird der spezifische Agent zugewiesen 
            steps {
                echo 'Ausführung der Stage 3'
            }
        }
    }
}

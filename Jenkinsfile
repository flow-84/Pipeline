pipeline {
    agent none // Kein Agent hier, weil später spezifischer Agent zugewiesen wird

    stages {
        stage('Stage 1') {
            agent { label 'my-ec2-agent' } 
                echo 'Ausführung der Stage 1'
            }
        }
        stage('Stage 2') {
            agent { label 'my-ec2-agent' }
            steps {
                echo 'Ausführung der Stage 2'
            }
        }
        stage('Stage 3') {
            agent { label 'my-ec2-agent' }
            steps {
                echo 'Ausführung der Stage 3'
            }
        }
    }
}

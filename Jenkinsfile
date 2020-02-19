pipeline {
    agent any 
    stages {
        stage('Paso 1') {
            steps {
               sh label: '', script: 'make' 
            }
        }
        stage('Paso 2') {
            steps {
                sh label: '', script: './a.out' 
            }
        } 
    }
}

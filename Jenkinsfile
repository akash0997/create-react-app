node {
    checkout scm 
    stage('Build') {
        steps {
        sh 'npm install'
        }
    }    
    stage('Test') {
        steps {
        sh 'npm test'
        }
    }
    stage('Deploy') {
        echo 'Deploying....'
    }
}

node {
    checkout scm 
    stage('Build') {
        sh 'npm install'
    }    
    stage('Test') {
        sh 'npm test'
       }
    stage('Deploy') {
        echo 'Deploying....'
    }
}

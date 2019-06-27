node {
    checkout scm 
    stage('Build') {
        'npm install'
    }    
    stage('Test') {
         'npm test'
       }
    stage('Deploy') {
        echo 'Deploying....'
    }
}

node {
    checkout scm 
    stage('Build') {
        steps {
        sh 'npm install'
        }
    }    
    stage('Test') {
         'npm test'
       }
    stage('Deploy') {
        echo 'Deploying....'
    }
}

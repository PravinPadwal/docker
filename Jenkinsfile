pipeline{
    agent {
        label 'built-in'
    }
    stages {
        stage ('docker'){
            steps {
                sh "chmod -R 777 /usr"
                sh "docker cp index.html kuldip:/usr/local/apache2/htdocs/"
                
            }
        }
    }
}

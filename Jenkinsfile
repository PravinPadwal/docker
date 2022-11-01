pipeline{
    agent {
        label 'built-in'
    }
    stages {
        stage ('docker'){
            steps {
                sh "chmod -R 777 index.html"
                sh "docker cp index.html kuldip:/usr/local/apache2/htdocs/"
                
            }
        }
    }
}

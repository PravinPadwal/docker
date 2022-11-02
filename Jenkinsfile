pipeline{
    agent {
        label 'built-in'
    }
    stages {
        stage ('docker'){
            steps {
   
                sh "docker cp index.html kuldip:/usr/local/apache2/htdocs/"
            }
        }
    }
}

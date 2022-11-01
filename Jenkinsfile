pipeline{
    agent {
        label 'built-in'
    }
    stages {
        stage ('docker'){
            steps {
   
                sh "docker cp index.html kuldip:/usr/local/apache2/htdocs/index.html"
                sh "docker exec -it kuldip bash"
                sh "chmod -R 777 /usr"
            }
        }
    }
}

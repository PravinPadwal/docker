pipeline{
    agent {
        label 'built-in'
    }
    stages {
        stage ('docker'){
            steps {
                sh "docker cp index.html pravin:/usr/local/apache2/htdocs/"
                sh "chmod -R 777 /usr"
            }
        }
    }
}

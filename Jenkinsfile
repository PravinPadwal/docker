pipeline{
    agent {
        label 'built-in'
    }
    stages {
        stage ('jay-1'){
            steps {
                sh "docker cp index.html jay:/usr/local/apache2/htdocs/"
                sh "chmod -R 755 /var"
            }
        }
    }
}

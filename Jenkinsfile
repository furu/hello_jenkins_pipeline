pipeline {
    agent { docker { image 'ruby' } }
    stages {
        stage('build') {
            steps {
                sh 'ruby --version'
            }
        }
        stage('test') {
            steps {
                sh "ruby -e 'puts 1 + 1'"
            }
        }
    }
}

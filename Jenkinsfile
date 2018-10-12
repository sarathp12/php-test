pipeline {
    stages {
        stage("Build") {
            agent { label 'php-build' }
            //...
        }

        stage("Test") {
            agent { label 'php-test' }
            //...
        }
    }
}

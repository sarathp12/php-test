pipeline {
    stages {
        stage("Build") {
            agent { label 'php-build' }
            //...
            echo "I am running"
        }

        stage("Test") {
            agent { label 'php-test' }
            //...
           echo "I am running again"
        }
    }
}

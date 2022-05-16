pipeline {
        stages {
            stage('Prepare') {
                steps {
                   // COMMON BUILD PIPELINE FOR DOCKER AND MAVEN PROJECT>
                }
            }
            stage('Download Shared Library') {
                steps {
                    script {
                        // invoke prepare() from common step.
                    }
                }
            }
            stage('Build') {
                steps {
                    script {
                        build()
                    }
                }
            }
        }
    }
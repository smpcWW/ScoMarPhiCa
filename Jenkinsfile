#!/usr/bin/groovy
//Declaritive Pipeline
pipeline {
    agent any
    environment {
        CC='clang'
    }
    stages {
        stage('Build') {
            steps { 
                sh 'echo "Building...."'
                //gcloud init
                //gcloud auth activate-service-account --key-file [KEY_FILE]
                
                //change here for jenkins test
                
                
                // In most cases, this is not desirable when running 
                // commands in a script or other automation. You can 
                // disable prompts from gcloud CLI commands by setting 
                // the disable_prompts property in your configuration 
                // to True or by using the global --quiet or -q flag.
                // Most interactive commands have default values when
                // additional confirmation or input is required. If 
                // prompts are disabled, these default values are used.
                // gcloud --quiet debug targets list

            }
        }

        stage('Test') {
            steps { 
                sh 'echo "Testing...."'
            }
        }
    


        stage('Deploy') {
            steps { 
                sh 'echo "Deploying...."'
            }
        }
    
}
}
#!/usr/bin/env groovy

    [$class: 'GithubProjectProperty',
    displayName: '',
    projectUrlStr: 'https://github.com/poolavenky123/repo2/']
    pipelineTriggers([githubPush()])

pipeline {
    agent any 

    stages {
        stage('Build') { 
            steps { 
                sh 'pwd' 
            }
        }
        stage('Test'){
            steps {
                sh 'java -version'
                
            }
        }
        stage('Deploy') {
            steps {
                sh 'ls'
                sh 'pwd'
            }
        }
    }
}

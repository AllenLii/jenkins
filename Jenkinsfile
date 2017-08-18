pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        node(label: '1404') {
          sh '''#!/bin/bash
set -e
set -x
echo Hello Build!'''
        }
        
      }
    }
    stage('Test') {
      steps {
        node(label: 'master') {
          bat 'echo Hello Test!'
        }
        
        input(message: 'Verify', submitter: 'jhli', submitterParameter: 'name')
      }
    }
    stage('Deploy') {
      steps {
        node(label: '1404') {
          sh '''#!/bin/bash
set -e
set -x
echo Hello Deploy!'''
        }
        
      }
    }
  }
}
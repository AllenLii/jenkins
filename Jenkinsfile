pipeline {
  agent none
  stages {
    stage('Build') {
      steps {
        sh '''#!/bin/bash
echo Hello World!'''
      }
    }
    stage('Test') {
      steps {
        sh '''#!/bin/bash
echo Hello Test!'''
      }
    }
    stage('Deploy') {
      steps {
        sh '''#!/bin/bash
echo Hello Deploy!'''
      }
    }
  }
}
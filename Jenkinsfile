pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        isUnix()
        sh '''#!/bin/bash
set -e
set -x
echo Hello Build!'''
      }
    }
    stage('Test') {
      steps {
        sh '''#!/bin/bash
set -e
set -x
echo Hello Test!'''
      }
    }
    stage('Deploy') {
      steps {
        sh '''#!/bin/bash
set -e
set -x
echo Hello Deploy!'''
      }
    }
  }
}
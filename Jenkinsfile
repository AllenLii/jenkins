pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''#!/bin/bash
set -e
set -x
echo Hello Build!'''
        isUnix()
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
pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        node(label: '1404')
        sh '''#!/bin/bash
set -e
set -x
echo Hello Build!'''
      }
    }
    stage('Test') {
      steps {
        node(label: '1404')
        sh '''#!/bin/bash
set -e
set -x
echo Hello Test!'''
      }
    }
    stage('Deploy') {
      steps {
        node(label: '1404')
        sh '''#!/bin/bash
set -e
set -x
echo Hello Deploy!'''
      }
    }
  }
}
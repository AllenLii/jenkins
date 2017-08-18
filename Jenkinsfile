pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''#!/bin/bash
echo Hello World!'''
        node(label: '1404')
      }
    }
    stage('Test') {
      steps {
        sh '''#!/bin/bash
echo Hello Test!'''
        node(label: '1404')
      }
    }
    stage('Deploy') {
      steps {
        sh '''#!/bin/bash
echo Hello Deploy!'''
        node(label: '1404')
      }
    }
  }
}
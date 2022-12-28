pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sleep(time: -2, unit: 'SECONDS')
        sh '''#!/bin/bash

echo "npm start"'''
      }
    }

  }
  environment {
    task = 'demo'
  }
}
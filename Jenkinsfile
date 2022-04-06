pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''#!/bin/bash



echo " print hostname"
hostname -i



echo " Print Memory details"
free -h



echo " Print CPU details"
mpstat



echo "Print Disck details"
df -k'''
      }
    }

  }
}
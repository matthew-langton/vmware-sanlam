pipeline {
  agent any
  stages {
    stage('vCenter Connection') {
      steps {
        powershell 'Connect-VIServer v006384.mud.internal.co.za'
      }
    }
  }
}
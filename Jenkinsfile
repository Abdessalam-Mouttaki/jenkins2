pipeline {
  agent any
  stages {
    stage('') {
      steps {
        powershell 'cd C:\\Users\\AbdessalamMouttaki\\Desktop\\POE_M2i_SE23-200140\\Selenium_Webdriver'
        powershell 'pytest test_Authentication.py'
      }
    }

    stage('Ok') {
      steps {
        echo 'Tout est Ok'
      }
    }

  }
}
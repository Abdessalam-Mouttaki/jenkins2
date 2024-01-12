pipeline {
  agent any
  stages {
    stage('Selenium_Test') {
      steps {
        powershell 'python -m pytest C:\\Users\\AbdessalamMouttaki\\Desktop\\POE_M2i_SE23-200140\\Selenium_Webdriver\\test_Authentication.py'
      }
    }

    stage('Ok') {
      steps {
        echo 'Tout est Ok'
      }
    }

  }
}
pipeline {
  agent any
  stages {
    stage('Git CheckOut') {
      steps {
        git(url: 'https://github.com/oralabuser/BlueOcean_Pipeline.git', branch: 'main')
        echo 'Successfully Checkout from GitHub!!'
      }
    }

    stage('Compile') {
      steps {
        bat 'Compile.bat'
        echo 'Compiled Successfully!!'
      }
    }

  }
}
node {
   stage('Preparation') {
      git 'https://github.com/C-Aumayr/SimpleWebApp.git'
   }
   stage('Build') {
      bat "gradlew.bat clean test"
   }
}
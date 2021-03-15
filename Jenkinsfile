node {
   stage('Preparation') {
      git 'https://github.com/C-Aumayr/SimpleWebApp.git'
   }
   stage('Build') {
      sh "./gradlew.bat clean test"
   }
}
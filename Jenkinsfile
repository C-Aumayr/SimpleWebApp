node {
 stage('Preparation') {
  git 'https://github.com/C-Aumayr/SimpleWebApp.git'
 }
 stage('Build') {
  bat "gradlew.bat clean test"
 }
 stage('Deploy') {
  sh "git push https://git.heroku.com/agile-lake-06850.git"
 }
}

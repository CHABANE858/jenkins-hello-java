node {
  stage('clone') {
      git branch: 'main', url: 'https://github.com/CHABANE858/jenkins-hello-java.git'
}
  stage('Build') {
      sh 'javac Main.java'
    // some block
}
  stage('Run') {
    sh 'java Main.java'
}
}

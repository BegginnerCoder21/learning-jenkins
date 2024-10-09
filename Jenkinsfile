node {
    stage('clone the project') {
        git branch: 'main', url: 'https://github.com/BegginnerCoder21/learning-jenkins.git'
    }
    stage('build the project') {
        sh 'javac Main.java'
    }
    stage('run the project') {
        sh 'java Main'
    }
}

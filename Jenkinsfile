node {
    stage('SCM checkout'){
        git 'https://github.com/lakshmaiah212/java.git'
    }
    stage('compile-package'){
        sh 'mvn package'
    }
}

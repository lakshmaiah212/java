node {
    stage('SCM checkout'){
        git 'https://github.com/lakshmaiah212/java.git'
    }
    stage('compile-package'){
        def mvnhome = tool name: 'maven', type: 'maven'
        sh "${mvnhome}/bin/mvn package"
    }
}

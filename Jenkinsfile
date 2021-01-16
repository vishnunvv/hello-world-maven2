node{
  stage ('SCM Checkout') {
    git 'https://github.com/vishnunvv/hello-world-maven2'
    }
  stage ('Compile Package'){
    def mvnHome = tool name: 'maven3', type: 'maven'
    sh "${mvnHome}/bin/mvn package'
    }
}

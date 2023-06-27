node{
    stage('Clone'){
        git 'https://github.com/business-intelligence-integration/projetDevOps1.git'
    }
    stage('Build'){
        sh label: '' script: 'javac src/main/java/com/example/demo/DemoApplication.java'
    }
    stage('Run'){
        sh label: '' script: 'java Main'
    }
}
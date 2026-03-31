node {
    stage('Clone') {
        git branch: 'main', url: 'https://github.com/LylDrey/jenkins-helloworld.git'
    }
    stage('Build') {
        sh label: 'label', script: 'javac Main.java'
    }
    stage('Run') {
        sh label: 'label', script: 'java Main'
       
     }
}


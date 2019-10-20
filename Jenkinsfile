pipeline {
agent any
stages {
    stage ('git') {
    steps{git 'https://github.com/muraliyantrapati/vasu.git'}    
    }
stage ('build') {
    steps{sh label: '', script: 'mvn clean'
        sh label: '', script: 'mvn install'
    }    
    }
    
}
}
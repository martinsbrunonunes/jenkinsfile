node {
    stage ('Checkout SCM'){
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/martinsbrunonunes/jenkinsfile.git']]])
    }
    stage ('Static Code Analysis'){
        echo 'Code Analysing'
    }
    stage ('Build'){
        echo 'Building'
    }
    stage ('Unit Testing'){
        echo 'Testing'
    }
    stage ('Delivery'){
        echo 'Delivery'
    }
}
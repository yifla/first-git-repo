properties([[$class: 'JobLocalConfiguration', changeReasonComment: ''], pipelineTriggers([pollSCM('* * * * * ')])])
node {
    stage("clone"){
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/yifla/DevOps14.11.git']]])
    }
    stage("shoe files"){
        sh "ls -l"
    }
}

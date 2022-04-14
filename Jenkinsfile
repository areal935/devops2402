properties([parameters([string(defaultValue: 'areal', description: 'what is your name?', name: 'name')]), pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage('one'){
        git "https://github.com/areal935/devops2402.git"
    }
    stage("bla"){
        bat "dir"
    }
}

properties([pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("clone"){
        git "https://github.com/adiabr/myrepo.git"
    }
    stage("bla") {
        bat "dir"
    }
}

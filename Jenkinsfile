properties([pipelineTriggers([githubPush()])])

node {
    stage("clone") {
        git "https://github.com/shahar5/MySoftware.git"
    }
    stage("show files") {
        bat "dir"
    }
}
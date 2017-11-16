node {
    stage("Stage 1") {
        checkout scm
        bat "echo Stage 1 timeout commencing..."
        bat "ping -n 5 127.0.0.1 > nul"
        bat "echo Stage 2 finished %DATE% %TIME%"
    }

    stage("Stage 2") {
            checkout scm
            bat "echo Stage 2 timeout commencing..."
            bat "ping -n 5 127.0.0.1 > nul"
            bat "echo Stage 2 finished %DATE% %TIME%"
    }
}

node {

    stage("Stage 3") {
            checkout scm
            bat "echo Stage 3 timeout commencing..."
            bat "ping -n 5 127.0.0.1 > nul"
            bat "echo Stage 3 finished %DATE% %TIME%"
    }

}
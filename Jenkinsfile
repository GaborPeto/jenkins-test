node {
    stage("Stage 1") {
        checkout scm
        bat "gradlew build"
    }

    stage("Stage 2") {
            checkout scm
            bat "gradlew build"
        }
}

node {
    stage("Stage 3") {
        checkout scm
        bat "gradlew build"
    }
}
def imageName = 'jfmajer/movies-marketplace'

node ('workers') {
    stage('Checkout') {
        checkout scm
    }
    stage('Build') {
        docker.build(imageName)
    }
}

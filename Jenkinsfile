node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'docker') {

        def customImage = docker.build("qwerty0901/test:v1")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
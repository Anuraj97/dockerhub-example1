node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'Anuraj97-dockerhub') {

        def customImage = docker.build("anuraj97/dockerhub-example")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}

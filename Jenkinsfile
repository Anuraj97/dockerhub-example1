node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'Anuraj97-dockerhub') {

        def customImage = docker.build("anuraj97/anuranga")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}

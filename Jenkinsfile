node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerhub') {

        def customImage = docker.build("anuraj97/anuranga")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}

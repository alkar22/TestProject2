node {
    def app

    stage('Clone repository') {
        /* Let's make sure we have the repository cloned to our workspace */

       echo 'HELLO-WORLD-1'
    }

    stage('Build image') {
        /* This builds the actual image; synonymous to
         * docker build on the command line */

        echo 'HELLO-WORLD-2'
    }

    stage('Test image') {
        /* We test our image with a simple smoke test:
         * Run a curl inside the newly-build Docker image */

        echo 'HELLO-WORLD-3'
    }

    stage('Push image') {
        /* Finally, we'll push the image with two tags:
         * First, the incremental build number from Jenkins
         * Second, the 'latest' tag.
         * Pushing multiple tags is cheap, as all the layers are reused. */
       echo 'HELLO-WORLD-4'
    }
    stage('Deliver image') {
        /* We test our image with a simple smoke test:
         * Run a curl inside the newly-build Docker image */

        echo 'HELLO-WORLD-5 -by KADER'
    }
}

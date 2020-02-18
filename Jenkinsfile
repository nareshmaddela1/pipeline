node {
    def app

    stage('Clone repository') {
       
        /* Let's make sure we have the repository cloned to our workspace */

        checkout scm
    }

    stage('Build image') {
        
       echo 'buiding the application'
    }

    stage('Test image') {
        /* We test our image with different tests in parallel:
         * Run a curl inside the newly-build Docker image */
        echo 'test successful'
        /*we will setup manual approval before pushingh to deploy stage*/

        
    }
        stage('Test image') {
        /* We test our image with different tests in parallel:
         * Run a curl inside the newly-build Docker image */
        echo 'test successful'
        /*we will setup manual approval before pushingh to deploy stage*/

        
    }
    
     /*stage('Push image') {
        
        input "push to prod?"
        
        Finally, we'll push the image with two tags:
         * First, the incremental build number from Jenkins
         * Second, the 'latest' tag.
         * Pushing multiple tags is cheap, as all the layers are reused. 
        docker.withRegistry('https://registry.hub.docker.com', 'docker-hub-credentials') {
            app.push("${env.BUILD_NUMBER}")
            app.push("latest")
        }
   
    }
     */
}

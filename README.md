# simple-node-js-react-npm-app

Approach to Assignment
Forking the Repository
I started by forking the original repository simple-node-js-react-npm-app into my own GitHub account.
Setting Up Jenkins for Local Development
I created a Jenkins pipeline to automate the process of fetching the required npm packages, building the website, and serving it locally.
The Jenkinsfile in the root of the repository defines the stages of the pipeline, including installing dependencies, building the application, and serving it.
I configured Jenkins to run the pipeline and trigger builds whenever changes are pushed to the repository.
Accessing the Website and Jenkins Server
After a successful build in Jenkins, the website is accessible on localhost through port 3004.
The Jenkins server is also accessible on localhost through port 3000.
I added annotations in Jenkins to specify the npm packages used to build the repository.
Additionally, I included a button in Jenkins to manually execute the build process through the Jenkins interface.
Connecting MongoDB and Mongo-Express
I created a separate Jenkins pipeline to pull the latest versions of MongoDB, Redis, and Mongo-Express from the public Docker registry.
These images were then built as containers locally using Docker.
I connected the Mongo-Express frontend and MongoDB using the following access credentials:
Username: ati
Password: ati1234

### Infrastucture: Docker.

 It's example how to : 
 
 * Setting up NGINX proxy for Tomcat
 * Using NGINX for storing static content, and proxying dynamic content from Tomcat.
 * Deploying Spring Boot application to Tomcat using docker-compose.
    
 >NGINX, Tomcat, MongoDB are running each in its own container.
 
 For running application: 
 + Clone ore download this project.
   ```
   $ cd path/to/nginx-tomcat-proxy
   $ docker-compose up
   ```
   
Open browser and follow the link: 

http://localhost

And you will see Library's Welcome Page.
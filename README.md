# nodejs
Basic node.js code in docker 

## Goal Of This Project
The goal of this container image is to provide an example for running simple PHP with Httpd/Apache webserver in a container which follows the best practices and is easy to understand and modify to your needs.

## How to Use?
First of all, Pull the docker images from https://hub.docker.com/r/nayakasbl/php-httpd
<pre><code>docker pull nayakasbl/php-httpd</code></pre>
Then run the docker images which you have pull it before. You can modify 2020 as a port of PHP container. 
<pre><code>docker run -p 2020:80 nayakasbl/php-httpd </code></pre>
After that, see the output or the result on http://localhost:2020. 

Now you have the simple PHP running container!! 

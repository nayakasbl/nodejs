# nodejs
Basic node.js code in docker 

## Goal Of This Project
The goal of this container image is to provide an example for running simple PHP with Httpd/Apache webserver in a container which follows the best practices and is easy to understand and modify to your needs.

## How to Use?
First of all, Clone all the container component  from https://github.com/nayakasbl/nodejs
<pre><code>gh repo clone nayakasbl/nodejs</code></pre>
Then run the docker images which you have pull it before. You can modify 2020 as a port of PHP container. 
<pre><code>docker run -p 2020:80 nayakasbl/php-httpd </code></pre>
After that, see the output or the result on http://localhost:2020. 

Now you have the simple PHP running container!! 

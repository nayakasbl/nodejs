# nodejs
Basic node.js code in docker 

## Goal Of This Project
The goal of this container image is to provide an example for running simple Node.js in a container which follows the best practices and is easy to understand and modify to your needs.

## How to Use?
First of all, Clone all the container component  from https://github.com/nayakasbl/nodejs
<pre><code>gh repo clone nayakasbl/nodejs</code></pre>
Run command bellow to installs a package and any packages that it depends on.
<pre><code>npm install</code></pre>
Build the images with command bellow and do not forget to add the directory of the repository that you have cloned before.
<pre><code>docker build -t nodejs:latest (directory)</code></pre>
Then run the docker images which you have cloned before. You can modify 2020 as a port of Node.js container. 
<pre><code>docker run -p 2020:80 nodejs:latest </code></pre>
After that, see the output or the result on http://localhost:2020. 

Now you have the simple Node.js running container!! 

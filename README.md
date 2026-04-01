# docker-basic-learning
This repo contains a simple Docker project demonstrating Docker conceptes. It sets up a basic web server that listens on a port and displays a "Hello World!" message in your web browser.
# How it works
the Dockerfile takes your hello.js file and packages it into a self-contained container based on Node 8. when you run that container it starts that web server you wrote in hell.js listening on port 8888. this means when you open your browser to that address it accesses the running server inside the container and displays 'Hello World!'


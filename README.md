# docker-basic-learning
This repo contains a simple Docker project demonstrating Docker conceptes. It sets up a basic web server that listens on a port and displays a "Hello World!" message in your web browser.
# How it works
1-Before you begin pease make sure you have Docer installed on your machine. if you don't have it yet, you can install it by following the officia Ddocker documentation 
2-Clone this using this command: "git clone <repository URL>"
3-open the file in your termina using cd command 
4-To build the application image, run this command: "docker build -t <image_name> ."
5-To run it use: "docker run -p 8888:8888 <image_name>"
6-To validate it's running, open your browser and go to: "http locahost 8888". You should see the message "Hello World" on the page


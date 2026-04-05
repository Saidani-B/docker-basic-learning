# docker-basic-learning
This repo contains a simple Docker project demonstrating Docker conceptes. It sets up a basic web server that listens on a port and displays a "Hello World!" message in your web browser.
# How it works
1-Before you begin pease make sure you have `Docker` installed on your machine. if you don't have it yet, you can install it by following the official Docker documentation

2-Clone this repo and open folder using :
```bash
git clone https://github.com/Saidani-B/docker-basic-learning.git
cd docker-basic-learning
```
3-To build the application image, run this command
```bash
docker build -t <image_name> .
```
4-To run it use
```bash
docker run -p 8888:8888 <image_name>
```
5-To validate it's running, open your browser and go to: `http locahost 8888`. You should see the message "Hello World" on the page


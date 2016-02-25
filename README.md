# Flask + Docker example

This is a simple example of a Flask app running in a Docker container.

To run, 

1. sudo docker build -t flask_app_img .

2. sudo docker run -p 80:5000 -i -t flask_app_img


Then go to "http://localhost/".


# Brief exmplanation

The Dockerfile contains the steps to build a Docker container. This includes installing Python and pip, installing the ap dependencies, and running the app.

Once this container is built, we run it, redirecting our host port 80 to the container port 5000. We can then access the containerized app via our host port 80.

# Credit

The majority of this was taken from the excellent Digital Ocean documentation on Docker. You can find this here - https://www.digitalocean.com/community/tutorials/docker-explained-how-to-containerize-python-web-applications.




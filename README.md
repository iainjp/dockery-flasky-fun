# Flask + Docker example

This is a simple example of a Flask app running in a Docker container.

To run, 

1. sudo docker build -t flask_app_img .

2. sudo docker run -p 80:5000 -i -t flask_app_img


Then go to "http://localhost/".

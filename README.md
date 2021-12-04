# rest-api-microservice-docker

Technologies used:
AWS
Python
Flask
Flask Restful
Docker


Now lets use that Dockerfile to build an image which will later be used to make a container:
docker build -t flaskbookapi:1.0 

Now, finally! Fire up a container with the image we just built!
docker run -p 5000:5000 --name FlaskBookAPI flaskbookapi:1.0

And Boom! Out API is up and running! On a Docker container
 docker run -p 5000:5000 --name FlaskBookAPI flaskbookapi:1.0
 * Serving Flask app "api" (lazy loading)
 * 
 * Environment: production
   WARNING: This is a development server. Do not use it in a production deployment.
   Use a production WSGI server instead.
 * Debug mode: off
 * Running on http://0.0.0.0:5000/ (Press CTRL+C to quit)



source: https://dev.to/swarnimwalavalkar/build-and-deploy-a-rest-api-microservice-with-python-flask-and-docker-5c2d

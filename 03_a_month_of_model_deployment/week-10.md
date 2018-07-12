# Docker containers 

Last week, we looked at packaging and exposing our model via a Flask API. This week, we will look at putting that Flask App into a Docker container. There are many advantageous to having our model inside a Docker container. Amongst others, we can manage dependencies and make sure our application runs inside a standardised environment. Having our model inside a Docker container also means that our model can be integrated into an existing microservices application like any other microservice. 

This week, we want to: 

1. Package our Flask app into a Docker container
2. Run our container on a local host
2. Make POST calls to our App to GET predictions like when we deployed Flask straight onto our local host.  

Example [here](https://github.com/jeannefukumaru/flask-keras-docker-demo.git): 


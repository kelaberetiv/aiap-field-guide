# Exposing our model via a REST API 

When we deploy machine learning model, we would typically allow the model to serve predictions via a REST interface. A client, for example our application, can make POST a request to the API, which then returns a prediction. For example, a user might upload a picture of a cat to a web browser app, which then returns a prediction of what breed the cat belongs to. 

This week, we want to: 

1. Expose a pre-trained model as an API using Flask 
2. Test the API by making calls with Postman or CURL 

Resources: 
https://aiaptraining.blob.core.windows.net/www/model-deployment.html
https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world
http://flask.pocoo.org/docs/0.12/

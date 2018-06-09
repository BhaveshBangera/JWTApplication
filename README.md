# JWTApplication
This is a basic application built using Django-REST Framework. Here when a user is authenticated, he is provided a token (i.e. JSON Web Token) by the Authentication Server, with the help of which he is able to make an API Call to our Application. Our Application verifies the token and then only user gets access to API data.
We have used Postman HTTP Client, for request/response to/from server.
The user who wants to access the API data, first needs to provide valid credentials.
Once he provides valid credentials, he will recieve two tokens(one is access token and another one is refresh token).
Now with the help of access token he will be authorised to access the API data.
If the token doesnt match, then user won't be able to access the API data.

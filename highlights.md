

## 2025-10-27T13:06:48.194Z
- **10/27/2025, 2:06:29 PM** - https://medium.com/@poorva59/implementing-simple-jwt-authentication-in-django-rest-framework-3e54212f14da
  > In this article weâll learn how to use simple JWT authentication with the Django Rest Framework. Before we understand Simple JWT Authentication, lets understand what is JWT ?

- **10/27/2025, 2:06:34 PM** - https://medium.com/@poorva59/implementing-simple-jwt-authentication-in-django-rest-framework-3e54212f14da
  > JSON Web Token(JWT) also (pronounced âjotâ) is an open standard that is used to securely transmit the data or information between the client and server as a JSON object. Each JWT contains encoded JSON objects, which have set of claims. A claims may assert who issues the token, what are the permissions granted to the clients , or how long the token is valid. JWT are signed using cryptographic algorithm to ensure that the claims cannot be altered after the token is issued.

- **10/27/2025, 2:06:40 PM** - https://medium.com/@poorva59/implementing-simple-jwt-authentication-in-django-rest-framework-3e54212f14da
  > 3. Signature : It is most important part of JSON Web Token. Header and Payload is encoded using Base64url encoding. Then these two are concatenated with a separator. And whole code is provided to the client in the authentication process.


## 2025-10-27T13:07:41.759Z
- **10/27/2025, 2:07:26 PM** - https://medium.com/@poorva59/implementing-simple-jwt-authentication-in-django-rest-framework-3e54212f14da
  > In authentication process whenever a user or client wants to login to the web application, then user need to send their login credentials like username or password to server and request for a JWT token form the server.

- **10/27/2025, 2:07:30 PM** - https://medium.com/@poorva59/implementing-simple-jwt-authentication-in-django-rest-framework-3e54212f14da
  > Then server provide a JWT to the User only when user is verified. User then send that token to the server back to request for the accessToken to access the information of their own. The server checks and verify whether the accessToken is valid or not. If the token is verified then user can successfully login to their account and access their own information stored in the database.

- **10/27/2025, 2:07:36 PM** - https://medium.com/@poorva59/implementing-simple-jwt-authentication-in-django-rest-framework-3e54212f14da
  > Simple JWT is used for authentication in DRF, it basically generates a token for the client in the form of encoded JSON object.

Before starting to use simple jwt, lets first define models for the user data which we implement in our authentication mechanism.

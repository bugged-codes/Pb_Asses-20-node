# 4th Node hands-on

*Createed an appliction which contains Login page and Register Page.*

When  a user registers by giving Name, Phone, Email and Password, then :

An API /register gets created which saves the data and create the user.

1. API hashesh the password before saving data.
2. API returns correct status codes in success and failure scenarios.
3. After success, "User successfully registered" message is sent in response.
4. In case of failure, "User has not registered, please try again", error message is sent in response
5. The API accepts Name, Phone, Email and Password

Another API /login is also created. This api gets called when user tries to login from front-end application.

1. This API accepts email and password.
2. It also validates the user if registered or not.
3. If user is valid, then a JWT token is created and sent in the sucess response of the API.
4. In succcess scenario,"User has logged in successfully" message and token is sent. This token should be stored in local storage.
5. In failure scenario,"User is not registered" message is sent.

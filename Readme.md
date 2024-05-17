This is a Social App to create ,Read,Update and 
Delete users.

This App make use of bearer Token for security.

Sign up  page is the first api to start with this
project so as to have access to other endpoint.

[SIGN UP ](http://localhost:8080/auth/signup)
Method: Post
{
"name":"sanni",
"email":"sanni1@gmail.com",
"password":"Password@123"
}




[LOGIN USERS](http://localhost:8080/auth/login)
Method: Get




[GET USERS](http://localhost:8080/user/list)
Method:Get


[UPDATE USERS](http://localhost:8080/user/update)
Method: PUT
{
"id": 2,
"name": "sannie2",
"email": "sanni1@gmail.com",
"imageUrl": null,
"emailVerified": false,
"provider": "local",
"providerId": null
}

[DELETE USERS ](http://localhost:8080/user/delete/1)
Method:DELETE



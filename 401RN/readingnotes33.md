# Readings: Authentication & Production Server

## [JSON Web Tokens](https://jwt.io/introduction/)

- JWT is alway to pass information in a json way with it being secure. It is away for securely transmitting information between parties as a JSON object. This can be verified and trusted because it is digitally signed the JWTs can be signed using a secret. This is the signed tokens that you are so familiar with.

<u> What way information is pass in a uniform way </u>

1. Authorization
   > This is the most common scenario for using JWT. Once the user is logged in, each subsequent request will include the JWT, allowing the user to access routes, services, and resources that are permitted with that token. Single Sign On is a feature that widely uses JWT nowadays, because of its small overhead and its ability to be easily used across different domains.
2. Information Exchange
    > JSON Web Tokens are a good way of securely transmitting information between parties. Because JWTs can be signed—for example, using public/private key pairs—you can be sure the senders are who they say they are. Additionally, as the signature is calculated using the header and the payload, you can also verify that the content hasn't been tampered with.

## [DRF JWT Authentication](https://simpleisbetterthancomplex.com/tutorial/2018/12/19/how-to-use-jwt-authentication-with-django-rest-framework.html)

## [Django Runserver Is Not Your Production Server](https://build.vsupalov.com/django-runserver-in-production/)

## Videos

(Optional) [JWT with DRF](https://www.youtube.com/watch?v=Fhcn2qx-4VQ)
[Gunicorn](https://gunicorn.org/)
[Django Migrations Primer](https://realpython.com/django-migrations-a-primer/)

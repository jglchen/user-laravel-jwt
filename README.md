# Laravel API JWT Auth with Next.js Frontend

There are different types of API authentication systems available in the Laravel application, Like Laravel passport, Laravel sanctum and of course, you can also use JWT authentication. In this JSON Web Token Authentication for Laravel 10 tutorial, we will use JWT to create this API authentication in Laravel.

This project is trying to **use Laravel JWT API as the backend and set up authentication with Next.js as the browser frontend**. JWT API is incorporated to provide the authentication system.
When making requests using API tokens, the token should be included in the Authorization header as a Bearer token.
The Next.js React front pages are styled with Tailwind CSS to follow Laravel Breeze&apos;s default view designs. 
 

### Docker:
```
# Run the following two commands simutaneously with diffrent screen windows...

docker run -it -p 8000:8000 jglchen/laravel-auth-jwt php artisan serve --host=0.0.0.0
docker run -p 3000:3000 jglchen/user-next-jwt
```

### Docker Compose:
```
# At the root of the /user-laravel-jwt folder...
docker compose up
```

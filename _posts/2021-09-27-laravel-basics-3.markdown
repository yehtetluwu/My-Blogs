---
layout: post
title:  "Laravel Basics - 3"
date:   2021-09-27 12:20:47 +0630
categories: jekyll update
---
# Part 3

## Routing
> What is routing? 
> 
Before I answer that, What are routes in Laravel? Routes are basically something that will link you to the controllers and also let the users to jump through specified paths/query strings you made for you web app. It can be seen under routes folder. Most of the times, you have to define the routes in the **web.php** file. 
> 
It accepts http verbs like **get, post, put, patch, delete and options**. But any html forms with *post*, *put*, *patch*, *delete* are required to include CSRF token filed. You can also redirect if you are defining a route that redirects to 

- This is an example of a defined route.
  
`use Illuminate\Support\Facades\Route;`

`Route::get('/greeting', function () {`

`return 'Hello World'; });`


## Middleware
> Middleware is a mechanism for inspecting and filtering HTTP requests that goes into your application. Laravel has this awesome middleware which checks if the user is authenticated or not. If the user is not authenticated, it will take you to the log in screen and if the user is authenticated, it will allow futher requests into the application. And of course middlewares are not only for authentication. You can also write a log with it! 
Here is an example code for defining a middleware
- `php artisan make:middleware EnsureTokenIsValid`

## CSRF Protection
> CSRF has been mentioned above but what is it? It is called Cross-site request forgeries and is a type of malicious exploit where suspicious commands are being run from an authenticated user. 



### You can also check out [Laravel][Laravel] for more information on the official website.
![Laravel](/assets/images/laravel-8.png "Laravel-8")

[Laravel]: https://laravel.com/docs/8.x/releases
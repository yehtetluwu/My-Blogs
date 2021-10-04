---
layout: post
title:  "Laravel Basics - 4"
date:   2021-10-03 11:03:02 +0630
categories: jekyll update
---
# Part 3

## Controllers
> They can controll and organize request handling logics that are happening in your routes. You can also handle related requests under single class within containers. They can be found under `app/Http/Controllers/`. Controllers are also invokable. You can also generate an invokable controller by running this command with invokable tag `php artisan make:controller <Controller_Name> --invokable`. There is also resource controller which has CRUD classes defined for the users autimatically. All you have to do is use --resource with the command. You also have to make sure to call the model related to the requests you are defining in your controlller so that they are usable.

- This is an example controller class.
  

`use App\Http\Controllers\UserController;`

`Route::get('/user/{id}', [UserController::class, 'show']);`

## Models
> Since this was mentioned above, what are models? 
> 
Laravel uses Eloquent which is an object-relational mapper that can interact with the databases. When you use Eloquent, each database table has corresponding Models so that it can interact with the table. To create a model, run `php artisan make:model <model name>`. You can also add --migration option which creates and modifies database tables and columns if they need to be changed. 



### You can also check out [Laravel][Laravel] for more information on the official website.
![Laravel](/assets/images/laravel-8.png "Laravel-8")

[Laravel]: https://laravel.com/docs/8.x/releases
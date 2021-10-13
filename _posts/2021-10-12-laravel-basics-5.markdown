---
layout: post
title:  "Laravel Basics - 5"
date:   2021-10-12 14:16:05 +0630
categories: jekyll update
---
# Part 3

## Blade Templates
> Laravel has a really useful templating engine called blade. For starters, the blade files are stored in `resources/view` folder. An empty laravel project has a default page when you go to the localhost:8080. ![default_page](/assets/images/default_page.png "default-page")
Blade templates use .blade.php as their extension. What you are seeing here is from a blade file called "welcome.blade.php". Plain PHP codes can be used in blade template. You can also use routes and controllers to redirect the user to any blade pages you desire. Data can be displayed on the blade file by putting the variable inside { }. 

- This is an example route

`Route::get('/', function () {`

`return view('welcome', ['name' => 'Samantha']);`

`});`

## Using your own blade file
> For example, if you want to get rid of a default page and insert a page you made, you will have to first of all create database, migrate it, add model and controller file, add your own blade file under view, and lastly you can use routes to set your blade as default page. CSS can also be used to style your page as well. 

### Rendering JSON
> You can also initialize a javascript variable by inserting JSON code to your view. 

### If statements
> if statments can be deployed usind `@if` , `@elseif`, `@else` and `@endif`. 

- Here is an example if statment
  
```
@if (count($records) === 1)
    I have one record!
@elseif (count($records) > 1)
    I have multiple records!
@else
    I don't have any records!
@endif
```

### You can also check out [Laravel][Laravel] for more information on the official website.
![Laravel](/assets/images/laravel-8.png "Laravel-8")

[Laravel]: https://laravel.com/docs/8.x/releases
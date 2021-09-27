---
layout: post
title:  "Laravel Basics - 2"
date:   2021-09-16 8:16:47 +0630
categories: jekyll update
---
# Part 2

## Setting up a new project
> 
It is really easy and simple to set up a new project in Laravel. All you have to do is run this command using composer.
- `composer create-project laravel/laravel <project_name>`
> 
Then, you go into the directory of your project and you will have access to everything. 

## Hosting a web application with Laravel
> 
Just like prometheus or jekyll, when you want to host a web app or site on your local host, you will have to run this. But instead of the keyword like `jekyll serve`  , Laravel uses PHP. But make sure you are in the project directory before you host your web app.
- `php artisan serve`

## The default web app
> 
The first page you will see after you host your web app is the default Laravel page. It is rendered from the welcome.blade.php file under `/resourses/view` folder. It is written in html and you can mess with it on your first try. 

## Styling your blade
> 
There is a app.css file under public dirctory so that you can beautify your blade. But you can also use internal css or inline css to make your page more beautiful. 

## This is an example of a default page on laravel
![default_page](/assets/images/default_page.png "default-page")

### You can also check out [Laravel][Laravel] for more information on the official website.
![Laravel](/assets/images/laravel-8.png "Laravel-8")

[Laravel]: https://laravel.com/docs/8.x/releases
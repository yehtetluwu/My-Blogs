---
layout: post
title:  "React Basics - 1"
date:   2022-04-07 16:57:33 +0630
categories: jekyll update
---
# Part 1

## What is React
> React is one of the best and widely used javaScript library for building pretty websites and user interfaces. React is also used in a lof of famous websites such as facebook, instagram, reddit, uber and so on. 

## Getting Started
> So let's start with how to create an empty project in react. The first thing you will need to do is run `npx create-react-app@latest {project name}`. There will be a prompt asking you to continue and you can just hit y or type yes. 
![React_createProject](/assets/images/React_createProject.png "React Create Project") 

## Starting your project
> To start your react project, first you will need to go into the directory of your project folder. Then you will have to run `npm start` and a new tab will be opened in your browser. Notice if you didnt change anything in your newly created project and you ran it, it will show a react logo spinning and a text saying **Edit src/App.js and save to reload.**
![React_startProject](/assets/images/React_startProject.png "React Start Project")

## Editing your project
> Let's go to /src/App.js first and you will see a bunch of code under the function app. To customize your app, let's delete everything under return and replace it with the text **Hello world** in `<h1>`. You can't have more than one parent element in react so you wont be able to put multiple html elements or anything more than one. To fix it, all you have to do is add all of your code `<>` and `</>`. 
![React_helloWorld](/assets/images/React_helloWorld.png "React Hello World")
![React_helloWorld](/assets/images/React_helloWorld2.png "React Hello World")

### You can also check out [React][React] for more information on the official website.
![React_logo](/assets/images/React_logo.png "logo")


[React]: https://reactjs.org/
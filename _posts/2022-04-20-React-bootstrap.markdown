---
layout: post
title:  "React Basics - 2"
date:   2022-04-20 16:57:33 +0630
categories: jekyll update
---
## Single Page and Multi Page web applications
> Single-page web applications are websites where when you click something, it won't reload the page. Instead, it will just fetch the json data and display the new data. Multi-page applications are when you click something on the website, you will see a refresh whenever there is a new data on them. Single-page web applications are becoming more popular and big tech companies are starting to use them. Some examples of single-page web applications are Gmail, Facebook, Netflix, Google Maps, etc. Amazon and Ebay use multi-page web applications.  

## Creating a multi-page web applications with React
>  To create a multi-page web app, first you will have to create a react app obviously just like the previous blog. After creating the app, you will have to import the necessary components from React router dom. To do this, place this code `import { BrowserRouter as Router, Route, Routes } from 'react-router-dom';` to your App.js file. Then you can start creating different pages you want for example - about us page or something else. The important thing to remember is, in the App.js file, you can choose to make some components show up on every page. For example, you can choose to show the nav bar or search bar on every other pages. All you have to do is leave the code for those components in the App.js file. But if you also want to make your App.js file clean, you can create a seperate .js file for the nav bar and import it to the App.js file. 

## Linking the pages with React Router Dom
> Next, you will have to set up `<Router> <Routes> <Route path='/' element={<Home />} /> <Routes/> <Router/>`. For every differnet page you want to add, you will have to specify it under the Routes tag. You will also have to import those pages at the top of your App.js file. 
![React_ImportPages](/assets/images/React_importPages.png "React Import Pages")
![React_Router](/assets/images/React_router.png "React Router")

## Next Step
> After that, all you have to do is start flling the `href` values for every redirections you want and you will have your own multi-page web application with react!

### You can also check out [ReactBootstrap][ReactBootstrap] for more information on the official website.
![React_logo](/assets/images/React_logo.png "logo")


[ReactBootstrap]: https://react-bootstrap.netlify.app/
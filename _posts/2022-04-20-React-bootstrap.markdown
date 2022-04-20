---
layout: post
title:  "React Bootstrap"
date:   2022-04-20 16:57:33 +0630
categories: jekyll update
---
## Bootstrap
> Bootstrap is an front-end open source software that is mainly designed for mobile screen websites. Bootstrap has a lot of pre-built componnents, JavaScript plugins and SASS variables as well as responsive grids.   

## Getting Started
> Implementing bootstrap in React is really easy. The very first step you will have to do is installing it. To do this, you have to run `npm install react-bootstrap bootstrap`. The next step would be to import the any components you need. There are two ways you can import your components which are importing only the components you need and importing the whole library. Importing the specific components you need is recommended because otherwise, the whole library will be downloaded which will narrow down the amount of code to the client. To import individual components, you have to run `import Button from 'react-bootstrap/Button';` and to import the whole library, you can run `import { Button } from 'react-bootstrap';`.  

## The next step
> Next, you will have to import the css stylesheet because if you don't, the components you used in your app won't be styled. To do this, you can run `import 'bootstrap/dist/css/bootstrap.min.css';`. You can also override the bootstrap default variables by using your own Sass file. You can just import your own custom Sass file by creating it first, add the code you want to change, import the bootstrap in that custom Sass file and the import your custom Sass file to the main Sass file. 
![ReactBootstrap_Scss](/assets/images/ReactBootstrap_Scss.png "React Bootstrap Scss")

## Other way of Customization
> You can also overide the variables of some bootstrap components in your CSS file. For example, bootstrap buttons has their own predefined color classes which are **primary**, **secondary**, **success**, **warning**, **danger**, **light** and **dark**. And then there is custom button class where you can set the button to your own color. You can change the color in `.btn-outline-custom { }`. 
![ReactBootstrap_Custom](/assets/images/ReactBoostrap_Custom.png "ReactBootstrap Custom")

### You can also check out [ReactBootstrap][ReactBootstrap] for more information on the official website.
![React_logo](/assets/images/React_logo.png "logo")


[ReactBootstrap]: https://react-bootstrap.netlify.app/
---
layout: post
title:  "HTML Basics - 1"
date:   2021-11-08 13:07:08 +0630
categories: jekyll update
---
# Part 1

## What is HTML?
> What we are seeing on the screens of our laptops, phones, ipad, etc when we go to any websites are mostly written in HTML language. It was first invented by Tim Berners-Lee in 1993. Later html version 4 became official standard in 1999. And then we now have html5. 

## The declaration
> When we write a html document, we have to start with `<!DOCTYPE html>`, which is basically informing the browser to expect a html document. The `!doctype` is not case sensitive and so is the html after. 

## The default template
> The default template for html5 looks like this. Everything between the `<head> </head>` tag is going to be the head of the document. What's written in `<title>` is how it's going to be called on the tab of your browser.  `<meta>` tag can be removed nowadays and it's not thta important anymore. Everything that goes into the `<body>` tag will be what you see on your page. In the example below, you will see the `Hello world` words on your browser. 

```
<!doctype html>
<html>
<head>
    <title>Example html page</title>
    <meta name="description" content="Our first page">
    <meta name="keywords" content="html tutorial template">
</head>
<body>
    Hello world
</body>
</html>
```

<br>

![hello_world](/assets/images/hello_world.png "hello-world")

## The footer
> Althought the footer tag wasn't specified in the above example, it can added if you want to. It's basically what you see at the bottom in most pages. Attached at the bottom is an example of how a footer can be designed to look pretty so it's a pretty useful part. All the stuff will go under `<footer> </footer>` tag. 
![footer](/assets/images/example_footer.png "footer")

### You can also check out [html][html] for more information on the official website.
<br>

![html_logo](/assets/images/html_logo.png "logo")

[html]: https://html.com/
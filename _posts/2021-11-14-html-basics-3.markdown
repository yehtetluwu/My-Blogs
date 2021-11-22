---
layout: post
title:  "HTML Basics - 3"
date:   2021-11-22 13:16:38 +0630
categories: jekyll update
---
# Part 3

## CSS
>WHat is CSS is? CSS is cascading style sheets. It's used to design your webpage how ever you want. There are three types of CSS. Even though CSS is not part of HTML, I decided to talk about it because most beautiful websites you see on the internet are party written in CSS. I will be only going over how CSS works so that it will make us understand the relationship between HTML and CSS. 

## Types of CSS
>There are three types of CSS to beautify your webpage.
* Inline CSS
* Internal CSS 
* External CSS

## Inline CSS
> Inline CSS is using CSS inside the HTML tag. Inline CSS is good when you only want to make a little change to your tag or a specific tag without changing the other tags of the same name. Note that you can put as much attributes you want inside but if you only put one, you don't need `;`. Otherwise, you'll need to use `;` to seperate the attributes. Inline CSS also has highest priority and it will load the fastest. But keep in mind that, if there are a lot of inline CSS on your html page, it will take longer to load the entire site.
![inline_CSS](/assets/images/inline_CSS.png "inline_CSS")
>As you can see, there are two hello worlds in the same `<h1>` tag and inline CSS allow us to design those separately. You can do this with internal CSS or external CSS as well but there are extra steps if you want to do it.

## Internal CSS
> Internal CSS is using the `<style>` tag in the `<head>` of your html page. Internal CSS has priority after inline CSS. I personally don't use Internal CSS because I want to make my html document as simple as possible. 
![internal_CSS](/assets/images/internal_CSS.png "internal_CSS")

## External CSS
> To link an external CSS file to an html document, you must first say to your html document that you will be using CSS from this file. To do that, you will have to put `<link rel="stylesheet" href="<Path_to_your_CSS_file">` inside the `<head>` tag. Then you can start designing your website.
![external_CSS](/assets/images/external_CSS.png "external_CSS")

## Commenting 
> To comment in html, all you have to do is to start with `<--`, comment what ever you want, then `-->`.
>This is an example comment.
`"<!-- BANNER -->"`

### You can also check out [html][html] for more information on the official website.
<br>

![html_logo](/assets/images/html_logo.png "logo")

[html]: https://html.com/
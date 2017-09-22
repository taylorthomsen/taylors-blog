Article Title: Build a static blog with Vue.js and Vuelog
Description:
In this tutorial, we will build a blogging application with Vue.js and Vuelog. Vuelog is a static site generator that parses markdown files to render our blog posts on the client side. In this way, we can build a feature complete blogging application while harnessing the power of markdown and Vue.js client-side interactivity.

Ideas to Present in Article:
- Overview of the application, what we will build and links to source code + demo
- Introduction to the Vuelog and how static site generators work
- Generate the application and add posts
- Deploy blog to Github Pages
- Conclusion 

# Build a static blog with Vue.js and Vuelog

In this tutorial we are going to go through building a static blogging application with [Vuelog](https://vuelog.js.org/#/home). Vuelog is built out of Vue.js and uses the [marked](https://github.com/chjj/marked) markdown parser and compiler under the hood. This means that we get the full reactivity power of Vue 2 and Vuex and the simplicity of writing our posts in markdown format. Vuelog was created in China and takes internationalization very seriously. If you have readers that speak different languages Vuelog is an especially good static blogging choice. Under the hood Vuelog uses [vue-i18n](https://github.com/kazupon/vue-i18n) to render different language content based on the user's preferences.

## The application 

Demo: http://connorleech.info/vuelog-starter/

Source code: https://github.com/connor11528/vuelog-starter

## Why static blogs?

A static blogging application means that all of our content is hosted on the client side. We do not need a server to handle incoming requests or a database like MySQL or MongoDB to store our content. Instead our application will be made up entirely of HTML, CSS and Javascript. This decreases our hosting costs, can increase performance and simplify our application.

In this tu

### Alternatives



### Steps
- Clone the Vuelog repo, install dep, start dev server
- internationalization is a core feature and baked into the project 
	-  `<!-- zh-CN:+ -->  <!-- zh-CN:- -->` in posts for other languages
- 

### Example post 
```
title: Author posts or pages
category: docs
date: 2017-01-13
------------------------------------
Start your post content here...
```
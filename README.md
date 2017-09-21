# [Vuelog](https://vuelog.js.org/)

> A backend-free blog system built on top of Vue.js

Article Title: Build a static blog with Vue.js and Vuelog
Description:
In this tutorial, we will build a blogging application with Vue.js and Vuelog. Vuelog is a static site generator that parses markdown files to render our blog posts on the client side. In this way, we can build a feature complete blogging application while harnessing the power of markdown and Vue.js client-side interactivity.

Ideas to Present in Article:
- Overview of the application, what we will build and links to source code + demo
- Introduction to the Vuelog and how static site generators work
- Generate the application and add posts
- Deploy blog to Github Pages
- Conclusion 

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


## Browsers Support

| <img src="https://myst729.github.io/assets/images/browsers/chrome/chrome_256x256.png" alt="Chrome" width="96" height="96"><br>Chrome | <img src="https://myst729.github.io/assets/images/browsers/edge/edge_256x256.png" alt="Edge" width="96" height="96"><br>Edge | <img src="https://myst729.github.io/assets/images/browsers/firefox/firefox_256x256.png" alt="Firefox" width="96" height="96"><br>Firefox | <img src="https://myst729.github.io/assets/images/browsers/opera/opera_256x256.png" alt="Opera" width="96" height="96"><br>Opera | <img src="https://myst729.github.io/assets/images/browsers/safari/safari_256x256.png" alt="Safari" width="96" height="96"><br>Safari |
| :------: | :------: | :------: | :------: | :------: |
| Latest ✔ | Latest ✔ | Latest ✔ | Latest ✔ | Latest ✔ |


## Build Setup

```bash
# install dependencies
yarn

# serve with hot reload at localhost:8080
yarn dev

# build for production with minification, also update documentation
yarn build

# build for production and view the bundle analyzer report
yarn report

# run unit tests
yarn unit

# run e2e tests
yarn e2e

# run all tests
yarn test
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

If you just want to write something, grab the latest release package [here](https://github.com/myst729/Vuelog/releases/latest).


## Documentation

https://vuelog.js.org/


## License

[MIT](http://opensource.org/licenses/MIT)

Copyright (c) 2016-2017 [Leo Deng](https://myst729.github.io/)

---
title: "What and Why Gatsby?"
date: "2019-03-01T22:40:32.169Z"
template: "post"
draft: false
slug: "what-and-why-gatsby"
category: "Web Development"
tags:
  - "Gatsby"
  - "CMS"
  - "Web Development"
description: "Building modern websites have become way easier with Gatsby becoming the popular kid in tech. Gatsby is known for its easy setup and blazing fast websites. It has powerful pre configurations which is helping in creating sites with incredible advantages."
socialImage: "/media/image-0.jpg"
---

Building modern websites have become way easier with Gatsby becoming the popular kid in tech. Gatsby is known for its easy setup and blazing fast websites. It has powerful pre configurations which is helping in creating sites with incredible advantages. Gatsby is React based and uses GraphQL as its query language for APIs, so folks already working on React & GraphQL can leverage their skills here. It is not that you cannot work with Gatsby if you don’t know GraphQL, but it’s good that you learn it as it helps save time when working with more complex sites.

![Gatsby Logo](/media/gatsby.jpeg)

Well, there are various factors that contributes to the blazing fast Gatsby site. Some of them are:

**Intelligent image loading** - gatsby-image is designed to help preload images and automatically crop the images for different screen sizes which in turn results in faster page load. It has amazing image processing capabilities which is powered by GraphQL and Sharp.That’s cool right, you don’t need to go through the trouble of resizing images before using it.

**Code splitting and prefetching** - Gatsby only downloads the files which are required on a particular route. It pre-fetches data for the parts of the site you are not looking at and only makes it available in the browser when needed by a particular component. Gatsby uses GraphQL to do all of this.

Among the incredible features that Gatsby provide, I just don’t want to miss out on talking about the automatic **Routing**. You can create routes just by creating files and naming them as you want the route to be. Any react component defined in src/pages/*.js will automatically become a page. For example, if you want a route such as ‘/about’, you just need to name your js file as ‘about.js’. Then you can link pages like -



```js
<Link to=”/about”>About</Link>
```

Well there is so much more to Gatsby. So go ahead, explore more and build something great with Gatsby.
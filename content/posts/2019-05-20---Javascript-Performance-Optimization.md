---
title: JavaScript Performance Optimization
date: "2019-05-20T22:40:32.169Z"
template: "post"
draft: false
slug: "javascript-performance-optimization"
category: "Web Performance"
tags:
  - "JavaScript"
  - "Performance"
  - "Web Development"
description: "Better performance of your web application leads to better user experience. There are various ways using which you can boost your application’s performance. Here are some of the ways that I found helpful in optimizing performance of JS applications."
socialImage: "/media/42-line-bible.jpg"
---

Better performance of your web application leads to better user experience. There are various ways using which you can boost your application’s performance. Here are some of the ways that I found helpful in optimizing performance of JS applications.

### 1. Use Async and Defer:

Async and defer are boolean attributes which can be loaded along with the script tags. They are useful for loading external scripts into your web page. How async works: When you load async along with the script tag, as soon as a script is encountered while the HTML parsing is in progress, the script is fetched in parallel. Once the script is fetched, HTML parsing stops and the script is executed. Then on completion of the script execution, HTML parsing continues. If you want to load external script which is not dependent on execution of any other script, use async. Async attribute does not guarantee the order of execution of scripts. How defer works: When you load defer along with the script tag, as soon as the script is encountered while the HTML parsing is in progress, the script is fetched in parallel. Once the script is fetched, HTML parsing continues again. Once the parsing is complete, the fetched script is executed. If there are multiple scripts which are dependent on each other, use defer.

## 2. Throttle and Debounce:

Both these concepts limit the rate of function calls/execution. They both are used for performance optimization of web applications. For example, suppose a user clicks on a button multiple number of times continuously. And on each click, say an API is called again and again. To limit the rate of API calls on the click event, throttling can be implemented. Throttling sets an amount of delay for the API to be called. Let’s take another example of a search bar. On a keypress event in the search bar, you can set a delay so that function/API call is made after a certain pause on the keypress. This method is known as debouncing.

## 3. Web Workers:

JavaScript is single threaded and it does not have any support for threaded execution. Web workers are scripts that run on a separate thread in the background. It is a feature of the browser. They perform tasks without interfering with the UI. Once a web worker is created they can send messages to your JavaScript code that created it by posting messages.

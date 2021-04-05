---
title: "Empathy Driven Development"
date: "2019-03-25T22:12:03.284Z"
template: "post"
draft: false
slug: "empathy-driven-development"
category: "Accessibility"
tags:
  - "Accessibility"
  - "a11y"
  - "web development"
description: "I know you are a kickass JavaScript developer!! But are you a good human too? Do you care about your product being accessible to everyone? There are more than one billion people globally with disability who may benefit from your product but aren’t able to."
socialImage: "/media/gutenberg.jpg"
---

I know you are a kickass JavaScript developer!! But are you a good human too? Do you care about your product being accessible to everyone? There are more than one billion people globally with disability who may benefit from your product but aren’t able to. The disability can be visual, hearing, cognitive or any muscular impairment, etc. Wouldn’t it be great if say your product was helping 100 people and with the concept of accessibility your product can help 100 more people? Accessibility is a concept wherein you make technology accessible for people with disabilities.

![Web Accessibility](/media/web-accessibility-101-the-basics_870x450.jpg)

## What is the problem with JavaScript + a11y?

With JavaScript the interactivity with the web pages have increased. For example, click and hover only events make your application difficult to use for keyboard only users. In single page applications, when navigating to a new route, the entire page does not reload but only the part of content that has changed. This is great for performance of the web page but the problem is until the entire page reloads, screen readers are not able to identify the changes on the page. (Screen reader is a tool that converts digital text into synthesized speech to help users with low vision.) And this is just one example where the difficulty occurs for people with disabilities.

## The Solution:

We need to use the functionality that JavaScript provides to enhance the accessibility of web.

+ For keyboard support, use keyboard interface events like keyup, keydown or keypress.
+ Another good practice would be to use tabindex="0" which allows elements other than links and form elements to receive keyboard focus. It places the element in the logical navigation flow, making it behave like a link on the page.
+ See to it that client-side view changes are known to screen reader users by announcing the change in page title, using ARIA live regions (ARIA live regions provide a way to programmatically show dynamic content changes such that it can be announced by assistive technologies).

Obviously these are not the only problem/solution to accessibility issues. There is much more to accessibility, maybe a topic for another few blogs. Till then try to keep up with the best practices.

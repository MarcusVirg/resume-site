---
title: 'Resplice'
image: '/img/RespliceLogoTempAlt.svg'
description: 'Resplice introduces a new way to share contact information, never ask anyone for updated info again.'
tags: ['React.js', 'PWA', 'Web', 'Javascript', 'Phoenix', 'Elixir']
fact: 'I think this project will eventually become a utility to the world!'
featured: true
---

Resplice introduces a new way to share contact information, never ask anyone for updated info again. This application is a PWA, built with react, that is currently in private Alpha stages. Will be moving into beta soon. Sign up form for the beta is available here: <a href="https://goo.gl/forms/x9a0zFdWLjm1X1lQ2" target="_blank">Resplice Beta Sign-up Form</a>

### My Role

For this project I came up with an original design for this mobile application in <a href="https://www.figma.com" target="_blank">Figma</a>. There were two of us working on this project during it's creation. My collegue and I iterated over the design of the application many times while building it to make sure the user flow made sense. After we felt good about this design. I started to implemented the front-end piece of the application. We decided to keep this application in the web using a <a href="https://developers.google.com/web/progressive-web-apps" target="_blank">Progressive Web App</a> framework. At this point the application is in it's Alpha stage but will be available soon.

### Project Difficulties

This project was my first real, full featured web application I have built. I had to learn react while building this project, so discovering new UI patterns in react was very common for me. When I learned a new pattern, I would refactor some of my code where using this pattern would make sense. Halfway through the project I decided to integrate typescript into the application, this added some complexity causing me to refactor my UI components again. A final struggle was dealing with the limitations of web apis for some of the device hardware, like accessing location or contacts on a phone.

### Solution

I had to stay patient with myself and my workflows. Learning while building is challenging, yet is very rewarding and personally increases my learning abiliy tenfold. To deal with Web and Browser API limitations, I would do hours of research and, in most cases, ship my own system to solve a number of problems.

### Notable Features

- Authentication Flow w/ no passwords
- Using "window rendering" to render huge lists of data
- Complex iteractions and gestures like swiping and tapping
- QR Code Readers and camera access
- Using Google API to import contacts

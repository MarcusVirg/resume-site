---
title: "Phishing Exercise - Fake Google Login"
link: "https://accounts-google.netlify.com/"
image: "/img/Google_2015_logo.svg"
description: "Phishing exercise I used for an organization drill at a company..."
tags: ["Phishing", "Vue.js", "Google", "Social Engineering"]
fact: "I built this in about 3 hours total"
featured: false
---

This was designed to be a phishing exersice I put together for my company.
I sent out a fake email that looked like it was coming from the president of the company, only she knew about the exercise. In that email, I gave instructions that the employee must login into their Company Google Account and change a certain setting. I gave a link to that setting, but the link went to the [phishing website](https://accounts-google.netlify.com/) instead. Once a user clicked the link and tried to log into the portal, that looks very similar to Google's login portal (September 2018), I would get their credentials in my backend system in plain text format. This would give me instant access to accounts that don't have 2FA Authentication enabled.

I used this to teach the employees about phishing emails and social engineering. I gave them some tips, noting things to look for when receiving a weird email or an email with links in them.
I cannot disclose the result of the exercise but it was a great learning exercise.

Fun Fact: I built this mock system in about three hours using Vue.js, it was fun :)

Some features I want to add:

- Optimize for mobile
- Once the user trys to login and gets sent to the error page, redirect them to the real google login page, so they can actually login.

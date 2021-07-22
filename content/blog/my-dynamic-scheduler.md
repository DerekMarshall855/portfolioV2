---
author: "Derek Marshall"
title: "My Dynamic Scheduler"
date: 2021-04-04
description: "Post about my dynamic scheduler"
tags: ["calendar, scheduler"]
---

A group academic project built by me and two others (team of three) in April 2021. This was the first full stack MERN application I had ever developed. Uses a ReactJS frontend and a NodeJS backend.

<!--more-->

This project was what taught me full stack development. It has a backend for storing users, tasks, and events. The application also uses fairly insecure authentication, with private and public paths for access based on login. This web app allows users to upload tasks and events to their personal calendar and will generate a daily schedule organized by task due date, estimated completion time, and difficulty. Out of the group of three I did the largest contribution, designing and implementing the entire backend, designing and implementing the scheduler algorithm, and using axios to connect the frontend and backend. I also got to practice my code review skills over discord with my other group members for the frontend of the project.

The code for this project can be found on my github or by following this [link!](https://github.com/DerekMarshall855/MyDynamicScheduler)

---

!['mydynamicscheduler calendar page'](/images/calendar.png)


{{< css.inline >}}

<style>
.emojify {
	font-family: Apple Color Emoji, Segoe UI Emoji, NotoColorEmoji, Segoe UI Symbol, Android Emoji, EmojiSymbols;
	font-size: 2rem;
	vertical-align: middle;
}
@media screen and (max-width:650px) {
  .nowrap {
    display: block;
    margin: 25px 0;
  }
}
</style>

{{< /css.inline >}}

---
author: "Derek Marshall"
title: "Bulletin Board"
date: 2019-03-21
description: "Basic client server application mimicking a public bulletin board"
tags: ["Networking, Client, Server"]
---

A basic client server application, allowing multiple users to connect to the server and post/share posts on a virtual bulletin board. Project developed in python and developed for academic purposes.

<!--more-->

This was my first client-server application. The bulletin board used a simple 2d array to keep track of where notes were pinned on the virtual board, allowing users to read posts in certain locations. The users could fetch posts of specific colours or areas from the servers bulletin board and read them on client side.

The code for this project can be found on my github or by following this [link!](https://github.com/DerekMarshall855/Bulletin-Board)

---

!['Bulletin Board'](/images/bulletin_server.png)


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
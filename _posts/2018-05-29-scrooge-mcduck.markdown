---
title: "Scrooge McDuck - Real-time dollar quoting device"
layout: post
date: 2018-05-29 00:00
tag: arduino
# image:
headerImage: true
projects: true
hidden: true
description: ""
category: project
author: skhaz
externalLink: false
---

![Screenshot](/assets/images/scrooge-mcduck.jpg)

### What it do?

This project was an overkill idea for a simple problem that I did purely for fun and to experiment with new things. Essentially, what it did was have a task scheduler that scheduled a process to run every hour. This process would collect the exchange rate of the Dollar compared to the Real, and then save it to Firebase. On the other side, I had a microcontroller with firmware written in C++ listening in real-time for the exchange rate. When it changed, it updated the display, and I would have an idea if it was the right time to convert my salary from dollars to reais.

### What has inside?

-   C++
-   Espressif ESP32
-   Google Firebase Functions

### Links:

-   Source code [https://github.com/skhaz/scrooge-mcduck-iot](https://github.com/skhaz/scrooge-mcduck-iot).

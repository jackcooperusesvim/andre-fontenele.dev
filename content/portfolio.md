+++
date = '2025-06-10T15:11:44-04:00'
title = 'Portfolio'
tags = ['professional']
+++
### Homeschool Co-op Database

The co-op database is a project I started working on with the goal of replacing the nightmare of an Excel sheet my local co-op was using to keep track of students, families, classes, teachers, registrations, payments, and more.

This project was also my first introduction to web development, and I’ve learned a lot over the many rewrites this project has undergone.  My most recent version (shown below), includes a hand-rolled authentication and primitive authorization system. I used constant-time hash-checking, and proper hashing and salting. I also implemented protections against CSRF (form-implemented), XSS, SQL-injection, and brute-force attacks. You only see the Classes table here, but I also designed a database schema for the other parts.<br><br>
[Github](https://github.com/jackcooperusesvim/CoopGo)
{{< youtube mwbyCCorNGU >}}

### Tic-tac-toe AI
This is a fun project I like to build to learn the basic syntax of a new language. It's a simple search algorithm (minimax) that can be used to play simple games.

I also have a similar project which plays mancala with a more advanced version of this algorithm. That one is written in Rust and also has the added difficulty of being a multithreaded incomplete search, requiring depth-limiting game tree calculations.<br><br>
[Github](https://github.com/jackcooperusesvim/tic-tac-toe-AI)
{{< youtube Rx5F_YPo7N0 >}}

### POSIX HTTP Server (WIP)
The goal of this project is to build a basic multithreaded HTTP server in C using just POSIX (technically glibc) functionality. To non-technical people this will sound no different from any other website, but developers know that the self-inflicted handicap of using only POSIX C is a huge deal. It requires re-implementing a key abstraction (the HTTP protocol) that developers use to facilitate web communication in their code.

After this project is working (at least with basic MIME types), I plan on building a simple and lightweight key-value store in C, which can then be used in combination with the server to create a full-stack app in Pure POSIX C/C++ (and DataStar/JS).

### Basic SSH DNS-esque
This one is a developer tool for people who have many computers they want to SSH into, but don't want to have to deal with changing IP addresses and keeping a proper DNS. It is a simple two-part system (client and server) which uses an S3 bucket as a SSOT to keep track of changing ip addresses between servers and clients.

[Github](https://github.com/jackcooperusesvim/dnsesque)

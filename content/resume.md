+++
date = '2025-06-10T15:11:44-04:00'
title = 'Resume'
tags = ['professional']
+++

# Introduction

## Areas of Expertise

Backend Web-Dev,
Software Engineering,
Data Analytics,
Data Science

## About Me

I started programming in 2019, mostly out of a desire to replicate what was at the time, the coolest technology on the market: AI Voice Assistants. So 14 year old me picked up some basic python, and got to work; writing long chains of if-statements to replicate the functionality I saw in Alexa and Google Home. My parents noticed this and encouraged me in it so that by the next year I started my first college class towards a Bachelors in Data Science.

I finished my degree this June, having matured through my passion for code into a smart and well-rounded programmer. Now, I am looking for a job in the software development space where I can begin to specialize by providing value to a team of excellent programmers, learning under their leadership, and programming like a madman full-time.

## Credentials

- Graduated TESU with a B.S. in Data Science (3.85 GPA)
- Completed courses on SQL and Python from Boot.dev (level 40 Scholar)

## Work Experience

**GCP Investments**, Remote - Software Engineer<br>
*(April 2025 - Present)*

Refactor Rust code for binary and network parsing to be more robust and maintainable
<br>
<br>

**Academic Center for Enrichment**, Middlesex Community College - Peer Tutor <br>
*(August 2022 - May 2024)*

Tutor college students in various mathematical disciplines from Calculus II to Statistics
<br>
<br>

**AEOP GEMS**, Natick Soldier Systems Center - Assistant Near Peer Mentor<br>
*(June 2022 - August 2022)*

Mentor teens and pre-teens working on STEM projects in Army Research Labs
<br>
<br>

# Skills
### Hard Skills

- **Technologies**: Git, Github, Linux, AWS<br>
- **Languages**: Python, Rust, SQL, C, Go, Java, Bash, Javascript/React<br>
- **Libraries**:
    - Python: Sci-kit Learn, Pandas/Polars, Selenium, Keras, Flask<br>
    - Go: Templ, SqlC, Echo
- **Concepts and Processes**: Design Patterns, HTTP and Networking, Cryptographic Encryption, Unit Testing/TDD, Shape Up Project Management

### Soft Skills
#### Learning
One of my greatest skills is the ability to learn deeply at a fast pace. When I encounter a new API, for example, one of the first things I naturally do is wonder how it's implemented under the hood. I enjoy the opportunity to, whenever I can, build tools from scratch rather than just importing them. I don't always do these re-implementations, but having experience doing these re-implmentations keeps me aware, whenever I am using a new library or tool, of how it is most likely to work, which saves significant time when learning new things.

#### Presenting
I learned public speaking in High-school, where I took classes from a local pastor and competed in the National Christian Forensics and Communications Association (NCFCA). I competed in the NCFCA in Speech for ~2-3 years and Lincoln-Douglas debate for 1 year.

# Projects
### Co-op Database

The Co-op database is a project I started working on with the goal of replacing the nightmare of an Excel sheet my local co-op was using to keep track of students, families, classes, teachers, registrations, payments, and more.

This project was also my first introduction to web development, and I've learned a lot over the it's many re-writes. My most recent version (shown below), includes a hand-rolled authentication and primitive authorization system. I used constant-time hash-checking, and were proper hashing and salting. I also implemented protections against CSRF (form-implemented), XSS, SQL-injection, and brute-force attacks. You only see the Classes table here, but I also designed a database schema for the other parts.

{{< youtube mwbyCCorNGU >}}

### Tic-tac-toe AI
This is a fun project I like to build to learn the basic syntax of a new language. It's a simple search algorithm (minimax) that can be used to play simple games.

I also have a similar project which plays mancala with a more advanced version this algorithm. That one is written in Rust and also has the added difficulty of being a multithreaded incomplete search, requiring depth-limiting game tree calculations.

{{< youtube Rx5F_YPo7N0 >}}

### POSIX HTTP Server (WIP)
The goal of this project is to build a basic multithreaded HTTP server in C using just POSIX (techncially glibc) functionality. To non-technical people this will sound no different from any other website, but developers know that the self-inflicted handicap of using only POSIX C is a huge deal. It requires re-implementation some key functionality (the HTTP protocol) that developers use to facilitate web communcation in their code.

After this project is working (at least with basic MIME types), I plan on building a simple and lightweight key-value store in C, which can then be used in combination with the server to create a full-stack app in Pure POSIX C/C++ (and DataStar/JS).

### Basic SSH DNS-esque
This one is a developer tool for people who have many computers they want to SSH into, but don't want to have to deal with changing IP addresses and keeping a proper DNS. It is a simple two-part system (client and server) which uses an S3 bucket as a SSOT to keep track of changing ip addresses between servers and clients.


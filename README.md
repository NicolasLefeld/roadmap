```
I made this repository to follow my own learning and share it with others!

I'll be completing it from time to time 🙂

🏁 So, let's get start it! 🏁
```

_I'll let all the titles with links to one useful source_

# Internet

![internet](img/internet.svg)

## [How does the internet work](https://www.youtube.com/watch?v=42aWAAqoUfI) 🌐

> The internet its a "wire" (infraestructure) that interconects the people (clients) arround the world. The client connects to that infraestructure and other system serves with information (For example, a web page), that system is called server. Its good to say, that the internet, es free and open. 

## [What is HTTP?](https://www.cloudflare.com/learning/ddos/glossary/hypertext-transfer-protocol-http/)

> Its a protocol for transfering information between network devices.  It defines how text, images and video (information) are transmitted on the web.

* [HTTP Method](https://developer.mozilla.org/es/docs/Web/HTTP/Methods)
    * Indicates the action that the HTTP request expects from the queried server. For example, two of the most common HTTP methods are ‘GET’ and ‘POST’; 
* [HTTP status code](https://httpstatuses.com/)
    * Is a 3-digit code most often used to indicate whether an HTTP request has been successfully completed. 

## [Browsers and how they work?](https://www.mozilla.org/en-US/firefox/browsers/what-is-a-browser/)

![browsers](img/browsers.svg)


> A web browser it's a software that'll retrieve information (The comunication it's handled with HTTP!) from the web and display it to you in a nice way to understand.

* Cookies 🍪
    * A website may need to store some data, and that data will be stored on a file, that file is called "a cookie". Those files are stored locally on you system, and when you access again to that web page, it'll read the file and retrieve that information, it maybe be some credentials, or preferences taht you set on the page.

## [DNS and how it works?](https://www.cloudflare.com/learning/dns/what-is-dns/) 📖

> For good understanding, let's call it like cloudflare does, "the phone book of internet"

* How it works?
    * It's simple. First you go to a web like google.com (A hostname), and you setted dns server will translate the hostname to the IP, that at the time of writing, it's "172.69.68.203" for that hostname. Tha IP locates the google server, it's like a street address is used to find a particular home.

* Why DNS exist?
    * Because nobody will want to remember "172.69.68.203" as an address to a website, right?. So you put the address that everyone knows, like "google.com" and then the DNS server translate it for you.

_There is a lot more involved in DNS servers, check the link at the title for more information._

## [What is Domain Name?](https://www.website.com/beginnerguide/domainnames/8/1/What-is-a-domain-name?.ws) 🏡

> Is the address where Internet users can access your website (Like in the past example, google.com) and they were developed and used to identify entities on the Internet rather than using IP addresses.

## [What is hosting?](https://www.website.com/beginnerguide/webhosting/6/1/what-is-web-hosting?.ws) 🖥️

>  Is a service that allows organizations and individuals to post a website or web page onto the Internet. A good and modern example for web hosting, is [heroku](https://www.heroku.com/)

# Basic front-end knowledge

![frontend](img/frontend2.svg)

## [HTML](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics)

> HTML **is not a programming language**. It's a markup language that defines the structure of your content. HTML consists of a series of elements, which you use to enclose, or wrap, different parts of the content to make it appear a certain way, or act a certain way. There is others markup languages as XML or SVG.

* HTML Element
    * A simple paragraph element
![1](https://mdn.mozillademos.org/files/9347/grumpy-cat-small.png)
    * The same paragraph element with a class attribute that contain extra information about the element that you don't want to appear in the actual content.
![2](https://mdn.mozillademos.org/files/9345/grumpy-cat-attribute-small.png)

## [CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS)

> Is a language of style rules that we use to apply styling to our HTML content, for example setting background colors and fonts, and laying out our content in multiple columns. You'll create a class or an ID on CSS, add some style and then apply it to the HTML documment.

## [JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript)

> Is a scripting or programming language that allows you to implement complex features on web pages 

* DOM
    * Represents a document with a logical tree. Each branch of the tree ends in a node, and each node contains objects. DOM methods allow programmatic access to the tree. With them, you can change the document's structure, style, or content.

* 2D/3D
    * Canvas provides a means for drawing graphics via JavaScript and the HTML "canvas" element. Among other things, it can be used for animation, game graphics, data visualization, photo manipulation, and real-time video processing. The Canvas API largely focuses on 2D graphics and the  WebGL API, which also uses the "canvas" element, draws hardware-accelerated 2D and 3D graphics.

# OS and General knowledge

![operativesystem](img/operativesystem.svg)

## [Terminal Usage](https://ubuntu.com/tutorials/command-line-for-beginners)

> I dont have more to say than, open the terminal and start doing stuff. You'll learn with the time, like "I want to copy this file to that location" and google it. With the time you will get faster and notice that it's faster to use the terminal than the file explorer (For the copy example)

## [How OS's work in general](https://www.cleverism.com/operating-system-os-guide/)

> The operative system interconects the hardware and software of a certain system and gives to the user an easy to use interface. 

## [Process Management](https://www.guru99.com/process-management-pcb.html#:~:text=Process%20management%20involves%20various%20tasks,to%20share%20and%20exchange%20information.)

> The OS its in charge of creation, scheduling, termination of processes. Those tasks need system resources, and the OS its in charge too. 

## [Threads and concurrency](https://medium.com/@akhandmishra/operating-system-threads-and-concurrency-aec2036b90f8)

> A Thread also called lightweight process, is basic CPU utilization

> Concurrency also called parallelization happend when various threads excecutes at the same time

![thread](https://miro.medium.com/max/544/0*cgAbgEkofShV4B5z.png)

## Basic terminal commands

> A list of useful linux commands [here](https://www.hostinger.com/tutorials/linux-commands)

## Memory managment

> The SO needs to manage the resources, one of those is the memory.

* Store the running process on primary memory
* Move the process to second memory if the process goes to "suspended" (Called SWAP)
* Avoid process A to enter the memory space from process B (It's en example)

## Interprocess communication

## I/O Managment

## POSIX Basics

## Basic Networking Concepts

# Learn a language

![programming](img/programming.svg)

> I'll be letting here some information about the languages that I found relevant on my career

## Java Script

* https://eloquentjavascript.net/
* https://github.com/getify/You-Dont-Know-JS/blob/2nd-ed/get-started/README.md
* https://github.com/bevacqua/es6
* https://jgthms.com/javascript-in-14-minutes/
* https://learnxinyminutes.com/docs/javascript/

## PHP

* https://www.guru99.com/php-tutorials.html
* https://www.tutorialspoint.com/php/index.htm
* https://laravel.com/

# Version control system

![versioncontrol](img/versioncontrol.svg)

## [Basic Usage of Git](https://www.youtube.com/watch?v=vR-y_2zWrIE&list=PLWKjhJtqVAbkFiqHnNaxpOPhh9tSWMXIF)

> Git is an Open Source Version Control Software (VCS). With Git every change that you make on your project, you can wrap it up and upload to the one on the Git, that is stored on a repository. 

Git command list [here](https://github.com/joshnh/Git-Commands)


## Repo hosting services 

I just have experience with GitHub, GitLab and BitBucket. If you need a recomendation, go with GitHub, or if you like the Open Source, with GitLab. 

As I said, GitLab its Open Source, so you can download and install it on your own server!

Here I let a list of other popular services

* [SourceForge](https://sourceforge.net/)
* [Cloud Source Repositories
](https://cloud.google.com/source-repositories)
* [AWS CodeCommit
](https://aws.amazon.com/es/codecommit/)

## [GitHub](https://guides.github.com)

> Oh.. GitHub.. I was so refused to use it at first, but now I love it. Once you catch the flow, u'll never let it go!. And remember, GitHub depends on Git, the main tools are provide by Git, but GitHub add collaborative tools and hosting with [GitHubPages](https://pages.github.com/)

For my own experience, start with an empty repository. Upload some stuff to it and breake it a ton!, delete it and start again until you catch the flow. I dont have more than that, just follow the [oficial guide](https://guides.github.com/) and you will be fine!. 

Just one tip. If you are using Unix based OS, install ZSh. You can use the alias "ggpush" for "git push origin master" and others like that. It's amazingly fast when you get used to it! (Or just create you own alias, here it's a [guide](https://www.tecmint.com/create-alias-in-linux/#:~:text=What%20you%20need%20to%20do,command%20you%20wish%20to%20alias.&text=You%20can%20then%20use%20%22wr,for%20your%20current%20terminal%20session.), follow the permanent aliases one)

# Data bases

![database](img/database.svg)

> A database is an organized collection of data, just that!

> I came across the dilemma... "Relational or Non relational?", and well, there isnt a right answer, it depends on the project that you are working. For example:

* Non relational are fast and are scalable. But for me, the main reason it's his rapid development without a hassle.

* Relational are structured and have ACID compliancy
    * ACID (Atomicity, Consistency, Isolation, Durability). ACID compliancy reduces anomalies and protects the integrity of your database. It does this by defining exactly how transactions interact with the database, which is not the case with NoSQL databases, which have a primary goal of flexibility and speed, rather than 100% data integrity. **But in my experience, you can handle transaction integrity with Mongoose for example**

## Relational DB's

> I just have experience with MySQL at the time of writing and... It's tough. This tipe of relational DB has it's own benefits

## Non relational DB's

## More about DB's

# API's

![server](img/server.svg)

# Catching

# Web Security

![security](img/security.svg)

# Testing

![testing](img/testing.svg)

# CI/CD

# Design and development principles

![design](img/design.svg)

# Architectural patterns

# Search engines

![search](img/search.svg)

# Message brokers

# Containers VS Virtualization

![container](img/container.svg)

# GraphQL

# Graph DB's

# Web Sockets

# Web Servers

# Building for scale

![scale](img/scale.svg)

# Keep lerning!


![Backend roadmap](https://roadmap.sh/roadmaps/backend.png)

# Credits to 
## [Kamran Ahmed](https://github.com/kamranahmedse) for the [roadmap project](https://roadmap.sh/) 💟

## [undraw](https://undraw.co/) for the beautifull svgs! 💟
# A Front-end Handbook for Beginners - Overview
An introduction to everyone who is a beginner in the Front-end world with little knowledge of IT and computers but has a wonderful enthusiasm in them and want to be a great web developer.

This handbook is a list of keywords that you can use to search for specific tutorials, videos, documents or references. These keywords are chosen base on our experience accumulated through many projects, so it may not be completed but can be improved over time. The reason we only list the keywords is that you can freely choose a source (i.e. documents, websites, videos, tutorials, books) of your favourite to learn. If you can’t find any source that you like, don't worry, we have a list of recommended sources that are easy to learn, fully documented and exact.

The content of this handbook will cover all the major languages and technologies that run the entire front-end world, from the simplest language HTML to the complex Javascript. In every section, there are quizzes and exercises for you to do. Quizzes are a list of small questions, it may test how well have you learnt throughout the section, but it may also test your searching, reading and thinking skills by asking about historical knowledge, use cases or the purpose of a particular concept. Exercises, on the other hand, are lists of exercises that require you to practice just like a real project, helps you understand what you have learnt and keeps the lessons in your mind for a long time.

# Prerequisites
These are skills and knowledges that you should be familiar with before start reading this handbook:
- **Basic programming** - You should know at least one programming language such as Pascal, C, C++, C#, Java, Python, etc.
- **English** - If you can reach here then you have the skill.
- **Computer basic** - You should know what the basic components of a computer are, what a binary number is, how do they understand your program.
- **A curious mind**.

# Outline
* [Basic concepts](Part-2)
* [Hypertext Markup Language](Part-3)
* [Cascading Style Sheets](Part-4)
* [JavaScript](Part-5)
* [Security](#security)
* [The Skill Triangle](#the-skill-triangle)


## Security
- DNS.
- Internet protocol: HTTP, HTTPS, Web socket, FTP, SSH, MQTT, etc.
- Cross-Origin Resource Sharing
- Content Security Policy
- XSS attack
- DDOS attack
- SQL injection
- Session hijacking, etc.
- Cryptography: symmetric encryption, asymmetric encryption, SSL, hashing, SHA, HMAC, JWT,etc.


## The Skill Triangle
### Coding
Coding skill is about how well you write code. It's not just about writing a program that works right, but also about your coding styles, programming paradigms, test cases and documentations.

Normally, when we want to do something programmatically, we will start coding to make a program. You start by opening your favorite IDE or editor and begin to code. Then you compile it and/or run it, if there are any bugs, you will fix it and try again. This process is very familiar to almost everyone who has ever written a program.

In most case, it's enough to build a small, simple software for personal usage. But for a big, complex software which involves many people to cooperate, it's not sufficient. You cannot write this kind of software by your own alone in a plenty of time, especially when the client demands a very close deadline which happens regularly in real life businesses. The only way to accomplish this is to work together, in a team or a company or even many companies.

There are some problems arise when working together that don't emerge on personal project. Let's start with an example, imagine you are working on a software project with a partner (let's call him John) and there is a deadline. The question is: How do you work with John? You may choose to split the project into mutliple modules so that you and John can work on different modules and avoid code conflict. Everything worked smoothly until John's module had some bugs that caused your system to fail. The deadline was near and you decided to help John to fix it. You started looking at the code and had no idea what was going on. The code had no comments, syntax was arbitrary, variable names were short and had no meaning. You didn't even know which algorithm and structure he is using because he has no documentation about them. Given no information, you gave up, your project failed. You may think that I'm doing my project by my own hand, I don't need to work together, why should I care? Are you sure that after a year or a month or even tomorrow, you can still fully understand what did you write in your code, aren't you? Now, you may wish that those situations won't ever happen to you.

To get rid of those situations or at least minimize its probability, there are things that you should follow:
- **Choose your coding styles**. Coding style is a set of rules or guidelines used when writing your program. It includes naming convention for variables, spacing, indentation, block placing, etc. Following a coding style can make your code easier to read, avoid errors like missing semicolons and reduce the pain of debugging. So when other people look at it, they won't feel bad at all. Some languages prefer different coding styles so you can choose one or more coding styles base on the language you are using. For a JavaScript programmer, we recommend using Airbnb JavaScript Style, but don't look at it now, you need to learning JavaScript first so just let it aside for now.
- **Choose your programming paradigms**. While a coding style touches your eyes by its presentation, a programming paradigm touches your thinking. It is a way, a method to solve, model, debug your program. Choose the right programming paradigm can help you to solve a problem easily with less effort and less bugs. Just like coding styles, these are chosen differently by different programming languages, C++, C#, Java prefer Object-Oriented Programming (OOP), some others such as JavaScript prefer Functional Programming (FP). There are other programming paradigms that worth learning, you can have a look at them on the Internet. Among them, we recommend you to learn OOP and FP first.
- **Testing**. Testing is the process when you have finish a program or a feature of a program, you then test it to determine whether it works as expected and meet the requirements or not. This is one of the most underestimated things by new programmers, but it it one of the most important part in software industry. Why? Because nothing can ensure that a software written by any programmer or developer can work perfectly. There is a probability greater than 0 that the software has some failed functionalities. Be able to use test efficiently can help you find them quickly, . There are many types and levels of testing which you should know, like unit testing, integration testing, regression testing, Beta testing, etc. As we said, testing is important. Thus, you should spend a lot of time learning and researching, but you don't have to learn it all alone. Reading through this handbook will help you practicing a lot. Don't be hurry.
- **Comments and documentations**. Comment and documentation is a way to tell and explain about your code, how it works, what it does, what we should give it and what it should give us. Comments have the flexibility to be used in lots of diiferent ways. They can be used as a todo list, a reminder, to declare authority or to log changes. Comment and documentation are like a part of your memories that is place physically outside of your brain. When the time passed and you look at your old code, you may not feel so familiar at first but thanks to them, you will soon understand and remember all stuffs, so do others when they look at your code. As you can see, they dramatically reduce your effort and time spending to understand the code. There are some standard for writing good comments and documentations. For JavaScript, we recommend you to use JSDoc but again not to hurry, just let it aside for a while.

So that anyone who inherits or joins your project could have an idea of what are you writing on your software.

### Problem solving
Problem solving is about how you find a solution for a problem and how good the solution is.

### Communicating
Communicating is about how well you communicate with other people in a team.
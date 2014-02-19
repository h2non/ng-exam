# ng-exam

> Are you ready to become a great developer in a real AngularJS based project? Let's see it!

> **beta!**

## About

**Do you want to start a new project with AngularJS?**

**Are you sure that developers are able to join the project?**

Be naughty and put them to the test!

This repository host a static Web application based on AngularJS, Express, Jade and Bootstrap
that can be used as seed project to provide a ready-to-use pre-configured development environment

It also provides a real back-end WebService powered by Node.js and Express that should be consumed 
by the front

## Target developers

- Front End Developer 
- Full Stack Web Developer
- JavaScript Developer
- Ambitious developers

### Prefered skills

Ideally you should be familiar:

- Node.js
- Jade
- MVVM frameworks

## Pre-requisites

Is required you have previously installed the following tools:

- [Node.js](http://nodejs.org)
- Grunt (`npm install -g grunt-cli`)
- Bower (`npm install -g bower`)

## Setup the environment

Clone/fork this repository (or just [download](https://github.com/h2non/ng-exam/archive/master.zip) the archive)
```
$ git clone https://github.com/h2non/ng-exam.git && cd ng-exam
```
Install node.js dependencies
```
$ npm install
```
Install bower dependencies
```
$ bower install
```

## The "exam"

### Goal

This exam aims to evaluate a general technical skillsets applied to a Web development
based on Angular taken from a well undestanding of the JavaScript language and the event-driven programming 
to a well the proper implementation and framework features usage

### Conditions

- You **can** create your own folder structure and sources files as you need
- You **cannot** use any JavaScript library that is not already provided
- As a great developer, you **should test** your code (however is not required a full test coverage, just focus on the most critical code)
- The Web is your friend, you **can** read documentation and search help
- You **cannot** mofidy the provided JSHint validation directives

### Duration

As recommendation, dependening of your desired developers filter level skillset, 
the exam could be done from **2 hours** for experienced developers until to **24 hours**
(that mean discarding the time taken installing and setting up the environment)

### Scenario

**To do!**

You have a seed Web application with an initial structure 

### Implementation requeriments

**To do!**

Given the existent login page...

### API WebService endpoints

All the back-end communication must be performed in JSON format

#### /api/user/login [POST]

#### /api/user/register [POST]

#### /api/users [GET]

#### /api/users/:id [GET]

#### /api/users/:id [DELETE]

#### /api/users/:

### Tips

- Focus on the requirements to satisfy
- Use the features that the framework offers you
- Remember [YAGNI][yagni], [KISS][kiss] and [DRY][dry] principles when you are coding

### Finally...

<img src="http://oi58.tinypic.com/2m3r9ly.jpg" width="220" />

## Useful links

- [Angular Guide](http://docs.angularjs.org/guide/concepts)
- [Angular Style Guide](https://github.com/mgechev/angularjs-style-guide)
- [Angular Overview](http://glennstovall.com/blog/2013/06/27/angularjs-an-overview/)
- [Angular Testing Guide](http://docs.angularjs.org/guide/dev_guide.unit-testing)

## Evaluation criteria

The order is irrelevant

- Requirements satisfied
- Design patterns and separation of concerns
- Code structuration and modularity
- Impletementation complexibility
- Proper use of the framework features and components 
- Proper JavaScript implementation 
- Coding conventions

## License

DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE

[yagni]: http://en.wikipedia.org/wiki/You_aren't_gonna_need_it
[kiss]: http://en.wikipedia.org/wiki/KISS_principle
[dry]: http://en.wikipedia.org/wiki/Don't_repeat_yourself

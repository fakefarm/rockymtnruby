# Draft

## Intro

- Today we're going to talk about adding a tool to your toolbelt. Having the right tool for the job. 

- Middleman is a site generator that compliments rails development. If you know rails, you basically already know middleman. It's a quick learning curve and it solves some problems in a faster and lighter way than rails can. So let's dive in.

## Plain-vanilla static web application.
- There are 4 components about middleman I'd like to touch on before I demo how to use middleman

### Rails-y stuff
- asset pipeline - slim/haml/coffee/sass
- data management with yml
- paritals - DRY
- Helper methods
- Gemfile
- ruby in files
- bash
- template generators
- custom extensions
- lots of great environment data in 'data' and 'page' type existing helper methods

### Hosting
- you can host for free on github by just simply pushing to a branch called `gh-pages`
- there's a deploy gem so you just type `middleman deploy`

### Static
- static enables caching, and thus is faster than loading from a database

### blogging
- middleman comes with a blogging engine so you can manage blogs there. 
(Not sure if I should do any comparisons with jekyl..)

### Plain-vanilla static web application.
- okay let's put this to work. 
- Rather than type it out, I'm going to simply paste all this code from gists;

        styles.scss
        index.slim
        gemfile
        config.rb
        food.yml

## AngularJS application with static data.
- a static site doesn't mean that it lacks live data. So, we can use any JavaScript Framework to do this. Let's use Angular to add some data about local Pizza shops in the area

        angular/js directory
        new_idex.slim

## AngularJS front-end with stub API.
(Is this the time to talk about the benefits of this process?)
- placeholder data,
- reduced coupling,
- developing at own pace

## AngularJS application using a real API.






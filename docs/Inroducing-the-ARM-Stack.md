Introducing the ARM Stack
=========================

__Deprecated__

## Description

## Abstract

## What Do I Get Out of It?
This session will show <x> workflows, tools, and techniques to improve overall application design.

## Prerequisites
Prior knowledge of Ruby on Rails and JavaScript. Familiarity with AngularJS.

## Required Installs
Before coming to this session, please install the following:
* [Ruby on Rails (RorR)](https://github.com/tmarrs/json-at-work/blob/master/appendix-a/Appendix-A-README.md#installing-ruby-on-rails-ror)
* [Middleman](https://middlemanapp.com/basics/install/)

## Session Length
40 minutes

## Notes
- AngularJS, Middleman, Rails
- Separation of concerns between front and back end

Middleman
---------
Static sites, but much more ...

With a static site
------------------
- Raw HTML, JS, CSS
- No Sass vs Less
- No CoffeeScript


With Middleman
--------------
- Separates front end from backend
- Consumes backend REST services
- You can choose AngularJS,
- Clean separation from Rails backend REST services.


ARM Stack - Angular / Rails / Middleman
---------------------------------------
Preferred over Yeoman:
- One environment
- Everything is Ruby-based - same environment.
- Performance benefits


With the emphasis on JS:
- Separate front-end from back-end
- Introduce a workflow

Potential Pushback: We're managing 2 repos.

Our Response:
- We can work on each repo separately.
- Oftentimes, there are 2 separate teams anyway - 1 on the front, the other on the back.
- We can switch implementations on either side.
- Safe place to be in the JS framework wars.
  - Switch framework if needed.
- Switch the backend if needed.

Summary: ARM Stack - Middleman Front End (RoR, AngularJS, CoffeeScript) connects to RESTful API (in RoR) on the backend. Great separation of concerns.

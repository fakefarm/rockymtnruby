# Brainstorm

_01/14/2015_

## Dave:

- AngularJS, Middleman, Rails
- Separation of concerns between front and back end

### Middleman

Static sites, but much more ...

### With a static site

- Raw HTML, JS, CSS
- No Sass vs Less
- No CoffeeScript


### With Middleman

- Separates front end from backend
- Consumes backend REST services
- You can choose AngularJS,
- Clean separation from Rails backend REST services.


### ARM Stack - Angular / Rails / Middleman

Preferred over Yeoman:
- One environment
- Everything is Ruby-based - same environment.
- Performance benefits


### With the emphasis on JS:

- Separate front-end from back-end
- Introduce a workflow

### Potential Pushback: We're managing 2 repos.

#### Our Response:

- We can work on each repo separately.
- Oftentimes, there are 2 separate teams anyway - 1 on the front, the other on the back.
- We can switch implementations on either side.
- Safe place to be in the JS framework wars.
- Switch framework if needed.
- Switch the backend if needed.

### Summary: 

_ARM Stack_ - Middleman Front End (RoR, AngularJS, CoffeeScript) connects to RESTful API (in RoR) on the backend. Great separation of concerns.

## Tom:

### Front end

Yeoman / AngularJS / Bootstrap on the front.

### Back end

~~Sails.js~~ 
- Rails


### Pros
- Same dev environment - JS
- Separation of concerns
- Same benefits as above

### Cons

- Different tooling: Yeoman vs Sails (maybe - we have to see)

Summary: Another stack (almost MEAN :-). Great separation of concerns. Possible tooling differences between front and back.


### Progressions:
- Show each stack.
- Start with the Front End.
- Model the JSON data and generate a stub service with Firebase.
- Iterate on the front end and upgrade the JSON model.
- Implement the backend that conforms to the model.
- Remove the stub service and replace with the real one.
- After implementing both stacks, mix and match to show that everything works together and that there's no implicit coupling between front and backend.



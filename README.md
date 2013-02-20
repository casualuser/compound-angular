# Coangular is CompoundJS and AngularJS

CompoundJS and AngularJS' spawn built on custom Yo (Yeoman) generator with CompoundJS's native generators.

## Project Setup

_How do I, as a developer, start working on the project?_ 

1. First run #> curl -L get.tachy0n.com | bash

2. Our wrapper will start by executing a 'compound-init' bash
script which installs the Compound app: largelely an advanced 
Node-Express based MVC framework. (Middle and server tier) 

3. Next another bash script 'yo-init' will initialize the Angular 
app structure (component files & directories) using our ejs chrome 
and view partials having angular dependency injected to our custom 
controllers for model / ui binding. (Client-side tier (Bower, Angular, PhantomJS))

 Finally, dev, testing, and deployment Coangular will use Grunt from Yo. 
We'll factor in functionality of 'compound server' and 'compound test'
into an extended coangular grunt.js by Yo. Though either Compound or Grunt
'server' and 'test' commands should work equally well, or not used at all 
by just using node . directly for dev/testing. 

## Testing

_How do I run the project's automated tests?_

### Unit Tests

1. `yo test`

### Development Mode

1. `grunt server`

### Deploying

1. `grunt build` -> < project >/dist
 

## Sources
- _Yeoman.io_
- _CompoundJS.com_
- _AngularJS.org_


## Licenses
MIT, BSD


Stay tuned. 
email peter at m ind like dawt calm

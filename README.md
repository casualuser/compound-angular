# Coangular is CompoundJS and AngularJS

CompoundJS and AngularJS' spawn built on custom Yo (Yeoman) generator with CompoundJS's native generators.

## Project Setup

_How do I, as a developer, start working on the project?_ 

1. First run   > curl -L get.tachy0n.com | bash <YourApp> 
   # Steps 2 and 3 are step 1's notes

2. Our wrapper will start by executing our 'compound-init <YourApp>' 
bash script which installs the Compound app: largelely an advanced 
Node-Express-based MVC framework. In order to fully initialize 
Angular components a default component will exist called "YourApp"
providing its orm class, view files, and crud controller.
(Middle and server tier) 

3. Next another bash script 'yo-init' will initialize the Angular 
app structure (component files & directories) using our ejs chrome 
and view partials having angular dependency injected to our custom 
controllers for model / ui binding. 
(Client-side tier (Bower, Angular, PhantomJS))

Depending on the components (Angular or Compound) being tested
and developed for you'll need to use 'grunt test' or 'compound test'
respectively. A cli coangular file will be provided to do integrated
deployments borrowing from each project's deployment methodology to 
achieve a Coangular web app / cluster. 

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

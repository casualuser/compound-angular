![Coengular Logo](http://vodbro.com/coangular.png)

Coangular is a Compound and Angular crossbreed of Yo (Yeoman) 
and Compound generators for a hybrid MVC-MVVM workflow & fullstack.

**Note:** Compound is itself more or less qualified as a "fullstack" in that
recent code allows UI to reflect controllers and ORM in the browser
which is similar to the goal of Angular -- to bind data to view templates
in the client.

Our goal is to use these underlying projects as-is, and perhaps
monkey patching code if necessary, in order to get a hybrid 
stack rolling.

## Project Setup

_How does a developer start working on a new project?_    
_Note: Steps 2 and 3 annotate step 1's actions_


1. First run   > curl -L get.tachy0n.com | bash \<YourApp\>

2. Our wrapper will start by executing our 'compound-init <YourApp>' 
bash script which installs the Compound app: an advanced Node-Express-based 
ORM & MVC framework. In order to fully initialize Angular components a default 
component will be created called "YourApp" providing a JugglingDB ORM class, view 
files, and crud logistics (controller & generic routes).
(Dev layer: Middle and server tier) 

3. Next another bash script 'yo-init' will initialize the Angular 
app's structural component files & directories using our ejs chrome 
and view partials while preparing for Angular DI into the 'clienstide' 
Compound controller for model ui binding.
(Dev layer: Browser and presentation tier (Bower, Angular, PhantomJS))

_While these two projects will coexist in the same root directory the Angular 
app will be in 'aapp/' and Compound in 'capp/' to keep their code & assets 
isolated since they're similarly structured. As testing goes on with Coangular 
we may end up merging it into a single application directory but for 
now we're making them that way to be safe._

_By default Coangular will use a Redis store you must perhaps install
manually as a prerequiste. It'll come pre-configured for local-only, no pw, DB:2 on :6379._


## Deploying and Testing 

Depending on the components being developed and tested: Angular or Compound, 
you'll need to use 'grunt test' or 'compound test' respectively. 
A coangular cli will be provided to do integrated deployments borrowing 
from each project's deployment methodology to achieves the Coangular web app / cluster. 

_How do I run the project's automated tests?_

### Unit Tests

1. `grunt test`

### Development Mode

1. `grunt server`

### Deploying

1. `grunt build` -> < project >/dist
 

## Sources
- _Yeoman.io_
- _CompoundJS.com_
- _twitter.github.com/bower/_
- _AngularJS.org_


## Licenses
MIT, BSD


Stay tuned. 
email peter at m ind like dawt calm

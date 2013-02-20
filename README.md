# _Project_

_Description: What does this project do and who does it serve?_

## Project Setup

_How do I, as a developer, start working on the project?_ 

1. _What dependencies does it have (where are they expressed) and how do I install them?_
2. _How can I see the project working before I change anything?_

## Testing

_How do I run the project's automated tests?_

### Unit Tests

1. `rake spec`

### Integration Tests

1. _Run other local services / provide credentials for external services._
2. `rake spec:integration`

## Deploying

### _How to setup the deployment environment_

- _Required heroku addons, packages, or chef recipes._
- _Required environment variables or credentials not included in git._
- _Monitoring services and logging._

### _How to deploy_

## Troubleshooting & Useful Tools

_Examples of common tasks_

> e.g.
> 
> - How to make curl requests while authenticated via oauth.
> - How to monitor background jobs.
> - How to run the app through a proxy.

## Contributing changes

- _Internal git workflow_
- _Pull request guidelines_
- _Tracker project_
- _Google group_
- _irc channel_
- _"Please open github issues"_

## License


compound-angular
================

CompoundJS and AngularJS' bastard lovechild built 
upon a custom Yo (Yeoman) generator combined with 
CompoundJS's own native generators.

The goal of this super project is to integrate Angular
two-way data binding with Compound components using simply 
a common generator wrapper (this project's code) we'll name 
'CompAng' for Yo using 'yo init CompoundAngular' 

Our wrapper will start by executing a 'compound-init' bash
script which installs the Compound app and handles all 
its requirements.

Next it will step through 'yo-init' another bash script 
which will initialize the app structure (component files & 
directories) using our ejs chrome and view partials having 
angular required and custom controllers ready for binding.


Stay tuned. 
email peter at m ind like dawt calm

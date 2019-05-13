![CF](http://i.imgur.com/7v5ASc8.png) LAB
=================================================

## Lab 00 - Deployment Workshop

### Author: Chris Kozlowski

### Links and Resources
* [Submission PR](https://github.com/401-advanced-javascript-cdk/lab00-deployment-workshop/pull/1)
* [Travis](https://travis-ci.com/401-advanced-javascript-cdk/lab00-deployment-workshop)
* [Heroku App](https://lab00-deployment-workshop.herokuapp.com/)

A lab to test Continous Integration and deployment with GitHub through Heroku and Travis-CI.

#### Overview
- Integrates Travis-CI with my class organization
- Implements rules on the master branch in GitHub to require tests to pass before a PR can be merged.
- Integrates Heroku to automatically deploy on changes to the master branch.  Automatically runs tests if changes are push directly to the master branch.
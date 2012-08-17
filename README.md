# handson-reddit

Node.js wrapper for the Reddit API

## Purpose

1. To create a nice node-friendly wrapper/client for the Reddit API.
2. To learn how to create an API wrapper and share it using superagent and request. (smackdown)

## Installation

We'll look at npm publish and make the project available via

> npm install _________ (project name here)

## Usage

### Simple

> var reddit = require('handson-reddit'); // working title
>
> reddit.r('funny', function (err, results) {
> 
> });

### Chainable

> reddit.r('funny').new().exec(function (err, results) {
> 
> });

Support new(), controversial(), hot()

### Interactive

> reddit.login(username, password, function (err, success) {
> 
> });

Plus more calls from https://github.com/reddit/reddit/wiki

## But Why?

## But How?

## The Tests

## Let's Do This!
![Serverless Application Framework AWS Lambda API Gateway](other/img/serverless_framework_readme_fire.gif)

Serverless Framework (BETA)
=================================
[![serverless](http://public.serverless.com/badges/v3.svg)](http://www.serverless.com)
[![npm version](https://badge.fury.io/js/npm.png)](https://badge.fury.io/js/npm)
[![dependencies](https://img.shields.io/david/serverless/serverless.svg)](https://www.npmjs.com/package/serverless)
[![license](https://img.shields.io/npm/l/serverless.svg)](https://www.npmjs.com/package/serverless)

This is a fork version of the serverless framework based on version 0.5.6.

Serverless is the application framework for building web, mobile and IoT applications exclusively on Amazon Web Services' Lambda and API Gateway. It's a command line interface that helps you build and maintain serverless apps across teams of any size.  It's also completely extensible via Plugins.  We believe AWS Lambda will be the focal point of the AWS cloud, and the Serverless Framework interprets AWS from Lambda's perspective.



## Features

* Run/test AWS Lambda functions locally, or remotely
* Auto-deploys, versions & aliases your Lambda functions
* Auto-deploys your REST API to AWS API Gateway
* Auto-deploys your Lambda events
* Support for multiple stages
* Support for multiple regions within stages
* Support for separate credentials per stage
* Manage & deploy AWS CloudFormation resources to each stage/region
* Project Variables allow staged/regional values in config files
* Project Templates reduce configuration
* Environment variable support
* Assign multiple endpoints and events to a function
* Interactive CLI dashboard to easily select and deploy functions and endpoints
* Optimize your Lambda functions for faster response times
* Support for API Gateway custom authorizers
* Project files can be published to npm
* 100% Extensible - Extend or modify the Framework and its operations via Plugins
* Powerful classes and methods for easy plugin development
* AWS best practices and optimizations built in
* A fantastic and welcoming community!

## Getting Started

Install The Serverless Framework via npm: (requires Node V4)

```
npm install serverless-framework-0.56 -g
```

You can either install an existing project or create your own.  We recommend starting out with the [Serverless-Starter](https://www.github.com/serverless/serverless-starter)

```
serverless project install serverless-starter
```

Or you can create your own project

```
serverless project create
```

Refer to our [documentation](http://docs.serverless.com) for more info.  Enjoy!

## Plugins
Serverless is composed of Plugins.  A group of default Plugins ship with the Framework, and here are some others you can add to improve/help your workflow:
* [Meta Sync](https://github.com/serverless/serverless-meta-sync) - Securely sync your the variables in your project's `_meta/variables` across your team.
* [Offline](https://github.com/dherault/serverless-offline) - Emulate AWS Lambda and Api Gateway locally to speed up your development cycles.
* [Hook Scripts](https://github.com/kennu/serverless-plugin-hookscripts) - Easily create shell script hooks that are run whenever Serverless actions are executed.
* [CORS](https://github.com/joostfarla/serverless-cors-plugin) - Adds support for CORS (Cross-origin resource sharing).
* [Serve](https://github.com/Nopik/serverless-serve) - Simulate API Gateway locally, so all function calls can be run via localhost.
* [Webpack](https://github.com/asprouse/serverless-webpack-plugin) - Use Webpack to optimize your Serverless Node.js Functions.
* [Serverless Client](https://github.com/serverless/serverless-client-s3) - Deploy and config a web client for your Serverless project to S3.
* [Alerting](https://github.com/martinlindenberg/serverless-plugin-alerting) - This Plugin adds Cloudwatch Alarms with SNS notifications for your Lambda functions.
* [Optimizer](https://github.com/serverless/serverless-optimizer-plugin) - Optimizes your code for performance in Lambda. Supports coffeeify, babelify and other transforms
* [CloudFormation Validator](https://github.com/tmilewski/serverless-resources-validation-plugin) - Adds support for validating your CloudFormation template.
* [Prune](https://github.com/Nopik/serverless-lambda-prune-plugin) - Delete old versions of AWS lambdas from your account so that you don't exceed the code storage limit.
* [Base-Path](https://github.com/daffinity/serverless-base-path-plugin) - Sets a base path for all API Gateway endpoints in a Component.
* [Test](https://github.com/arabold/serverless-test-plugin) - A Simple Integration Test Framework for Serverless.
* [SNS Subscribe](https://github.com/martinlindenberg/serverless-plugin-sns) - This plugin easily subscribes your lambda functions to SNS notifications.
* [JSHint](https://github.com/joostfarla/serverless-jshint-plugin) - Detect errors and potential problems in your Lambda functions.
* [ESLint](https://github.com/nishantjain91/serverless-eslint-plugin) - Detect errors and potential problems in your Lambda functions using eslint.
* [Mocha](https://github.com/SC5/serverless-mocha-plugin) - Enable test driven development by creating test cases when creating new functions
* [Function-Package](https://github.com/HyperBrain/serverless-package-plugin) - Package your lambdas without deploying to AWS.
* [Sentry](https://github.com/arabold/serverless-sentry-plugin) - Automatically send errors and exceptions to [Sentry](https://getsentry.com).
* [Auto-Prune](https://github.com/arabold/serverless-autoprune-plugin) - Delete old AWS Lambda versions.

## Consultants
These consultants use the Serverless Framework and can help you build your serverless projects.
* [Trek10](https://www.trek10.com/)
* [Parallax](https://parall.ax/) – they also built the [David Guetta Campaign](https://serverlesscode.com/post/david-guetta-online-recording-with-lambda/)
* [Just Serverless](http://justserverless.com)
* [SC5 Online](https://sc5.io)
* [Carrot Creative](https://carrot.is)
* [microapps](http://microapps.com)
* [Apiwise](http://www.apiwise.nl)
* [Useful IO](http://useful.io) - and [Hail Messaging](http://hail.io)
* [WhaleTech](https://whaletech.co/)
* [CloudNative](http://cloudnative.io//)
* [Hop Labs](http://www.hoplabs.com)
* [Webscale](https://webscale.fi/briefly-in-english/)
* [API talent](http://www.apitalent.co.nz) - who also run [Serverless-Auckland Meetup](http://www.meetup.com/Serverless-Auckland)

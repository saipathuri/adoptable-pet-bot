# Adoptable Pet Bot

> :feet: :cat: :dog: 

> Tweets adoptable pets (from Adopt-a-Pet API) using Serverless framework and AWS Lambda.

> Inspired by work on [Cute Pets Norfolk](https://github.com/Code4HR/CutiesInHamptonRoads)

[![Made with Serverless](https://img.shields.io/badge/serverless-⚡-yellow.svg?style=flat-square)](https://serverless.io)
[![Norfolk JS Inspired](https://img.shields.io/badge/NorfolkJS-inspired-f3df49.svg?style=flat-square)](https://norfolkjs.org)

## Install

With [node 4.3](https://nodejs.org/) installed, install the Serverless Architecture:

```
$ npm i -g serverless
```

Clone this repository

```
$ git clone git@github.com:lynnaloo/adoptable-pet-bot.git
```

Install dependencies

```
$ npm i
```

## Setup and Testing

Setup your Account Provider and Credentials

*   [AWS Lambda](https://serverless.com/framework/docs/providers/aws/setup)
*   [AWS account credentials](https://serverless.com/framework/docs/providers/aws/guide/credentials)

Run Unit Tests
```
npm test
```

Test Lambda Function locally
```
serverless invoke local -l -f tweetPet
```

## Deployment

Deploy Lambda Functions

```
$ sls deploy -v
```

## See Also

*   [Adopt-a-Pet API](https://github.com/lynnaloo/adopt-a-pet)
*   [Serverless Framwork](http://www.serverless.com)
*   [Cute Pets Norfolk](https://github.com/Code4HR/CutiesInHamptonRoads)

## License

MIT

# Taskprize

![screen](https://raw.githubusercontent.com/Brgraul/taskprize/master/screen.png)

## The problem :broken_heart:

To create a better world and increase understanding among each other, everyone have similar cognitive oportunities, or at least a common ground in this regards. 80% of human communication is non-verbal, and blind people are deprived of that valuable part. This is a barrier for emotional connections, and we are here to bring it down.

## Our solution :chart_with_upwards_trend:
Our Pheel Smartglasses provide audio feedback on the expression and reactions of the people in front of you. They count with an integrated camera and send synchronous images to the Azure Cloud for Sentiment Analysis. This feedback is communicated back to the user in the form of speech, transferred through a discrete bone conduction interface. 

## The Implementation :space_invader:
Along these 31 hours, we built a working Web Application that performs sentiment analysis based on webcam input and transforms the result in user actionable audio feedback. 

* Backend -> Node.js
* Frontend -> React.js
* Sentiment Analysis -> Azure Face API
* Text to Speech -> Azure TTS API

## Our Vision :earth_americas:

Our bigger picture is to implement this framework into a pair of glasses, that discretly scans and feedbacks the enviroment to the user in need. Using cameras for the face detection and bone conduction for communicating the feedback - enabling emotions for everyone!

\# ThinkBigStartSmall

[![Netlify Status](https://api.netlify.com/api/v1/badges/65064b42-5a8f-4981-b4ae-3c6e38ef8b04/deploy-status)](https://app.netlify.com/sites/dasks/deploys)

At Taskprice, we want to let you focus in the things you really care about by outsourcing microtasks.
The problem we found is the subjectivity of accomplishment of a task in certain fields, like it can be creative design or the editorial world.
Our users enjoy a simple flow through our web application: 1. They put up the task they want to outsource and how much are they willing to pay. 2. Freelancers take these tasks from the task pool and submit their proposals. 3. Their peers, thus experts in the field, rate the quality of the submitted proposals. 4. Once the time / max people have been reached, a smart contract is triggered paying the set amount to the top performer.


Each task creates a smart contract on an Ethereum test network. Tasks
include description, due date, and offered reward for completion.
Remote freelancers work on and complete tasks and verify the
completion by uploading a photo via IPFS as proof of work. Completion
could then be verified by votes of other freelancers on the platform
for example. Consensus triggers the smart contract and the reward
payment is sent.

> Project was developed during a 1.5-day smart contracts hackathon in May 2019.

![screen](https://raw.githubusercontent.com/siebenrock/smart-microtasks/master/screen.png)

## Smart Contracts

Smart contracts are one of the most powerful applications of
Blockchain technology. Once designed, coded and implemented on the
Blockchain, they are automatically executed whenever predefined
trigger-events occur. Through clever design and strict rule-based
execution of these contracts, it is possible to induce actors to act
justly, without middlemen like banks, governments or notaries.

## Project setup

Requires MetaMask extension.

```
npm install
```

### Compiles and hot-reloads for development

```
npm run serve
```

### Compiles and minifies for production

```
npm run build
```

### Run your tests

```
npm run test
```

### Lints and fixes files

```
npm run lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).

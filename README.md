# Taskprize

[![Netlify Status](https://api.netlify.com/api/v1/badges/65064b42-5a8f-4981-b4ae-3c6e38ef8b04/deploy-status)](https://app.netlify.com/sites/dasks/deploys)

<img src="https://raw.githubusercontent.com/Brgraul/taskprize/master/logo.png" alt="drawing" width="400"/>


## The problem :broken_heart:

Nowadays several platforms such as fiverr offer the possibility to outsource microtasks to freelancers. Customers of these platforms are frequently dissaftisfied with the outcome mainly for two reasons: 

- The outsourcer lacks expertise in the given domain, which makes the evaluation specially subjective
- The high variability in the quality of the deliverables 

## Our solution :chart_with_upwards_trend:

As pointed out by Justin M. Berg, fellow colleagues are the most accurate when it comes to predicting the success of innovative ideas. We offer our users a dApp for microtask outsourcing and collective evaluation of deliverables.

Our app flow comprises 4 simple steps: 
1. Contractors put up the task they want to outsource and how much are they willing to pay. 
2. Freelancers take these tasks from the task pool and submit their proposals. 
3. Their peers, thus experts in the field, rate the quality of the submitted proposals. 
4. Once the time / max people have been reached, a smart contract is triggered paying the set amount to the top performer.

## The Implementation :space_invader:
Along these 20 hours, we built a working dApp powered by a Solidity smart contract and off-chain storage thanks to IPFS. 

![screen](https://raw.githubusercontent.com/Brgraul/taskprize/master/screen.png)

* Backend -> Serverless, yay!
* Frontend -> Vue.js
* Smart Contract -> Solidity (Remix deployment)
* Off-chain storage -> IPFS distributed file system

## Our Vision :earth_americas:

Our goal is to become the defacto trust system in existing freelancer outsourcing platforms.


## Project setup :wrench:

*Requires MetaMask extension*

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

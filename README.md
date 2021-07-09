# dapp for certificate validation

Pre-requisites:
> node: 	^16.2.0
> npm: 		^7.10.0
> web3.js: 	^1.3.6

## Description
This project is aimed towards making a framework for a decentralized application(dapp) for validation of digital certificates.
It is to be considered an example project for Final Year Major Project Submission of Alok Kumar Patro and Ajay Kumar Pradhan for the year 2021, CSE, VSSUT, Burla

##This is a demo project and is using Expressjs for fast and easy deployment


## Running Locally

```
unzip the .rar file (Dapp for Certificate Validation)
cd "Dapp for Certificate Validation"
npm install
npm start
```

Your app should now be running on [localhost:3000](http://localhost:3000/).


## Future Planning
> This project can be extended to have a client side interface where a client can verify the certificates issues by the issuing authority on the go
> Improvements can be done by using a smart contract by using languages like solidity (while current validation are based on student enrollment number)
> This framework can be extended to be used for any products like validating consumer products, certificates, etc.


## Limitations
> Increasing complexity in the data may lead to increase in gas price of the ethereum, thus making the contract expensive in real world scenario
> Using private blockchain is a good idea but it defeats the purpose by centralizing the data instead


## Submitted by
> Alok Kumar Patro - 1702041036
> Ajay Kumar Pradhan-1702041034


#References
> https://certifaction.io/ (An industry level ethereum based eSigning platform to increase authenticity of certificates)
> A. Gayathiri, J. Jayachitra and S. Matilda, "Certificate validation using blockchain," 2020 7th International Conference on Smart Structures and Systems (ICSSS), 2020, pp. 1-4, doi: 10.1109/ICSSS49621.2020.9201988.
>http://ceur-ws.org/Vol-1816/paper-16.pdf (Certificate Validation through
Public Ledgers and Blockchains)
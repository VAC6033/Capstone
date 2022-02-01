# Udacity Blockchain Capstone

I am unable to deploy to Rinkeby. Still waiting to receive any Ether despite posting my address in a public post on Facebook as advised by faucet. Tried various other faucets, all seem to be exhausted.

The capstone will build upon the knowledge you have gained in the course in order to build a decentralized housing product. 

Run Zokrates

docker run -v ${PROJECT_PATH}:/home/zokrates/code -it zokrates/zokrates /bin/bash
zokrates compile -i square.code
zokrates setup
zokrates compute-witness -a 3 9
zokrates generate-proof
zokrates export-verifier

Test
truffle test


# Project Resources

* [Remix - Solidity IDE](https://remix.ethereum.org/)
* [Visual Studio Code](https://code.visualstudio.com/)
* [Truffle Framework](https://truffleframework.com/)
* [Ganache - One Click Blockchain](https://truffleframework.com/ganache)
* [Open Zeppelin ](https://openzeppelin.org/)
* [Interactive zero knowledge 3-colorability demonstration](http://web.mit.edu/~ezyang/Public/graph/svg.html)
* [Docker](https://docs.docker.com/install/)
* [ZoKrates](https://github.com/Zokrates/ZoKrates)

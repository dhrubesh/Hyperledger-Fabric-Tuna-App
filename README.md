# Hypeledger Fabric-Tuna-App

This application demonstrates the creation and transfer of tuna fish shipments between actors leveraging Hyperledger Fabric in the supply chain. We set up the minimum number of nodes required to develop chaincode. It has a single peer and a single organization.

Steps to run this project:

First, remove any pre-existing containers, as it may conflict with commands in this tutorial:

$ docker rm -f $(docker ps -aq)
---
Then, run the following command to start the Hyperledger Fabric network:

$ ./startFabric.sh
---
Install the required libraries and register the Admin and User components of our network, and start the client application with the following commands:

$ npm install
---
$ node registerAdmin.js
---
$ node registerUser.js
---
$ node server.js
---

*And you're good to go!*
# Hyperledger-Fabric-Tuna-App

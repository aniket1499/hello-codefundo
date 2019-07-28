# hello-codefundo
codefundo++ Phase 2:  Submit your Idea

We can solve a number of problems faced by the people involved in elections (directly or indirectly) by bringing the E-voting system in exercise. It will not only improve the operation of tasks for elections but also make it convenient for the people to vote in an election at any given time and from anywhere. It will increase the transparency, completeness (only voters have the right to vote and their votes are correctly counted), and verifiability (voters can check that their vote is correctly counted) of the entire election system.

A decentralized application on the Azure network. For demo we can write your first smart contract which will hold an election between two candidates and we will allow accounts connected to the network to vote in our election and we'll watch all the votes come in in real time as they happen we'll write tests against our smart contract to ensure that our code is robust and we'll deploy all the code in our smart contract to a local Azure blockchain we'll also write a client-side application that will allow users connected to the network to interact with our smart contract and vote in the election.

With the initial research we believe using these dependencies will be beneficial.

NPM: https://nodejs.org
Truffle: https://github.com/trufflesuite/truffle
Ganache: http://truffleframework.com/ganache/
Metamask: https://metamask.io/

The theory behind the system will follow __Ring Signature__

![alt text](https://upload.wikimedia.org/wikipedia/commons/3/34/Ring-signature.svg)

A group of entities each have public/private key pairs, (P1, S1), (P2, S2), ..., (Pn, Sn).
a ring signature: σ = (m, Si, P1,P2,……,Pn)
Anyone can check the validity of a ring signature given σ, m, and the public keys involved, P1, ..., Pn

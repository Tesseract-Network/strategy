# Strategy

Ideas, brainstorming, resources, etc...

## What we do

Here we describe what our product is about and what we do as a company.

I started from an idea that I wanted to develop, I found out that there could be some technical challenges in making it a competitive product (gas fees mainly), so I started looking at other ideas, in the [brainstorming section](#brainstorming) we explore them. Now, I decided to focus on just one [idea](#the-idea) (that is actually the first one) because those technical challenges seems to be overcome.

### The idea

We will create an extension of the x402 protocol, called z402, that is protocol similar to x402 that has 0 delay and trust built in, it should have some slightly higher fees tho (the protocol itself doesn't charge any fees, but the blockchains behind it yes, same for x402).

Our product will be a z402 facilitator that charges a small fee on each payment, to be more precise all of our software will be free and open source, but by how the protocol is built it's necessary to use some smart contract that has to be whitelisted (trusted), our product is the entire ecosystem around our own smart contract that earn us fees. Essentially we're not selling anything, we're creating a lot of free softwares that run by default our smart contract, it can be changed tho, but if a big a user base is built they will keep using our contract cause it's widely recognized as secure, moreover we provide the "official" software for z402 that adds accountability and visibility to our contract.

I initially thought of trying to merge z402 into x402, but actually if that's the case, then the x402 non profit association will control the visibility of our smart contract and products, since x402 si de facto controlled by Coinbase I don't see why they shouldn't put themselves in the spotlight instead of us... So probably I shouldn't aim for a merge but actually stress that our protocol is better and either overtake them or just compete.

Some particularly cool features of our protocol are:

- Zero blockchain induced delay (with x402 it ranges form hundreds of milliseconds to few seconds)
- Zero trust (with x402 sometimes, like with Base, you need to trust some proprietary infrastructure to get faster confirmation times)
- More blockchain support: you could add support for the Ethereum Mainnet (that at the moment is not supported by x402 and, with their current design, probably it will never be), XRP and other slower blockchains, you need to be sure that the gas fees are low enough to be a meaningful option.

### Brainstorming

We know that we want to get a share of the [Internet of Agents](https://arxiv.org/abs/2505.07176) market, now it's a matter of understanding what exactly we want/is the best to do.

We have multiple options so far:

- Ideas I believe the most in (in order):
  - Create an extension of the x402 protocol (you could call it z402 or something) that allows my idea of instant blockchain transactions to work. In particular, you could add support for the Ethereum Mainnet, that at the moment is not supported by x402 and, with their current design, is unlikely that it will ever happen because Ethereum is slow and the speed of x402 payments depends on the fact that the underlying blockchain is fast, with my idea the delay is 0 for any chain. There are some technical challenges tho, for example gasless transactions, how to actually extend the protocol and higher gas fees because we use smart contracts.
  - Create a facilitator that allows you to pay with fiat/crypto and receive fiat/crypto. I think this is a potentially powerful idea, but there are legal considerations to take into account (KYC, AML, etc).
  - Create an x402 facilitator with some unique feature. I thought about decentralization, you could run the facilitator on some decentralized cloud service
- Ideas that I believe less in:
  - Create a full network of agents that collaborate with each other to solve complex tasks and pay for each other services.
    I think there's a lot of competition in this field: there are many emerging protocols and eventually there will be one main of few main protocols that will be mass adopted and probably the choice won't be done because of the technical features but rather because of the community built around the protocol.
    You can still do it but you should carefully choose a stack that is/will be highly adopted and try to add something unique on top of it, the simple fact that brings together many stacks and gives a complete product could be enough to boost adoption.
  - Add a missing piece for the Internet of Agents: for example I'm not aware of a database of agentic services, I would make it distributed and free and then add an optional payed service on top of it (like MongoDB, you can download it free and host yourself but also you can run it in the cloud for a fee).

## Name

Choosing a name for this startup...

- Geometry related (because agent networks can be complicated, so the geometry of them, hence the names):
  - Tesseract: nice name (it's the most famous 4 dimensional shape), but all domains are taken, used in the wild for whatever. Ok but tesseractlab.net is available also tesseract.it, consider it
  - Tesserhack/Tesserhackt: I don't like them that much, but the domains are there
  - pentatope: another 4 dimensional shape, but more domains are available
  - polytope: $n$-dimensional generalization of polygons. Some domains are available
  - Choron: suffix used for 4 dimensional shapes, sounds good, many domains are available
  - Polychoron: general name for a 4 dimensional shape, many domains are available
  - Polykoron: fancy variation of polychoron, all domains available
- Payment related:
  - gentPay: remainds of "agent" and "pay", but [gent](https://www.merriam-webster.com/dictionary/gent) also means "graceful" or "gentleman"/"noble", giving a sense of exclusivity and elegance. The domains are available (.com is expensive, but it's there). I prefer this to "AgentPay" (actually used by Mastercard) because it looks less human, just for robots, in theory an agent enabled payment system should be available also to humans.
  - Paygent: gives even more the idea of "pay agent" and seems a full word, but I like it a little less, also some domains are already taken.

## Resources

### General

- [x402](https://www.x402.org/): A protocol by Coinbase and supported by Google to allow agents to pay for each other services using blockchain [A2A](https://a2a-protocol.org/latest/): A protocol by Google to allow agents to communicate and collaborate on tasks
  - [Official list of x402 facilitators](https://www.x402.org/ecosystem?category=facilitators)
- [PayAI](): Startup that runs an x402 facilitator, it has support for a lot of chains.
- [A2P](https://cloud.google.com/blog/products/ai-machine-learning/announcing-agents-to-payments-ap2-protocol): A protocol by Google to allow agents to pay for each other services using blockchain or traditional payment methods (Mastercard, Paypal, etc). For blockchain it uses x402.
- Decentralized cloud services: [FluxCloud](https://cloud.runonflux.com/), [EigenCloud](https://docs.eigencloud.xyz/products/eigencloud/eigencloud-overview), [akash network](https://akash.network/), [ICP](https://internetcomputer.org/), etc.)

### Programming

- [How to verify Ethereum signatures in Solidity](https://soliditydeveloper.com/ecrecover)

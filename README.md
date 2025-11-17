# Strategy

Ideas, brainstorming, etc...

## What we do

We know that we want to get a share of the [Internet of Agents](https://arxiv.org/abs/2505.07176) market, now it's a matter of understanding what exactly we want/is the best to do.

We have multiple options so far:

- Ideas I believe the most in:
  - Create an [x402](https://www.x402.org/) facilitator with some unique feature. I thought about decentralization, you could run the facilitator on some decentralized cloud service (eigenlayer, akash network, ICP, etc)
  - Create an extension of the x402 protocol (you could call it y402 or something) that allows my idea of instant blockchain transactions to work. In particular, you could add support for the Ethereum Mainnet, that at the moment is not supported by x402 and, with their current design, is unlikely that it will ever happen because Ethereum is slow and the speed of x402 payments depends on the fact that the underlying blockchain is fast, with my idea the delay is 0 for any chain. There are some technical challenges tho, for example gasless transactions, how to actually extend the protocol and possibly higher gas fees because we use smart contracts.
  - Create a facilitator that allows you to pay with fiat/crypto and receive fiat/crypto. I think this is a potentially powerful idea, but there are legal considerations to take into account (KYC, AML, etc).
- Ideas that I believe less in:
  - Create a full network of agents that collaborate with each other to solve complex tasks and pay for each other services.
    I think there's a lot of competition in this field: there are many emerging protocols and eventually there will be one main of few main protocols that will be mass adopted and probably the choice won't be done because of the technical features but rather because of the community built around the protocol.
    You can still do it but you should carefully choose a stack that is/will be highly adopted and try to add something unique on top of it, the simple fact that brings together many stacks and gives a complete product could be enough to boost adoption.
  - Add a missing piece for the Internet of Agents: for example I'm not aware of a database of agentic services, I would make it disributed and free and then add an optional payed service on top of it (like MongoDB, you can download it free and host yourself but also you can run it in the cloud for a fee).

## Name

Choosing a name for this startup...

- Tesseract: nice name, but all domains are taken, used in the wild for whatever
- Tesserhack/Tesserhackt: I don't like them that much, but the domains are there
- gentPay: remainds of "agent" and "pay", but [gent](https://www.merriam-webster.com/dictionary/gent) also means "graceful" or "gentleman"/"noble", giving a sense of exclusivity and elegance. The domains are available (.com is expensive, but it's there). I prefer this to "AgentPay" because it looks less human, just for robots, in theory an agent enabled payment system should be available also to humans.
- Paygent: gives even more the idea of "pay agent" and seems a full word, but I like it a little less, also some domains are already taken.

## Resources

- [x402](https://www.x402.org/): A protocol by Coinbase and supported by Google to allow agents to pay for each other services using blockchain [A2A](https://a2a-protocol.org/latest/): A protocol by Google to allow agents to communicate and collaborate on tasks
- [A2P](https://cloud.google.com/blog/products/ai-machine-learning/announcing-agents-to-payments-ap2-protocol): A protocol by Google to allow agents to pay for each other services using blockchain or traditional payment methods (Paypal, etc). For blockchain it uses x402.

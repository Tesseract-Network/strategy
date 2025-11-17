# TODO

## Notations

- z402 is "my protocol" (it's shorter and the "z" reminds me of the zero delay)

## List

- Create "fake MVPs" to validate your ideas:
  - MVP for z402: stress the fact that there's 0 seconds delay, that is fully decentralized and that is blockchain independent (you just need smart contracts). You can apply your idea to blockchains with low gas fees (also x402 assumes it), you can classify them by speed:
    - Slow blockchains: blockchains that take more than few seconds to settle a transaction. The advantage here is huge, you get 0 seconds confirmation time for your payment, it will cost a little more because of the gas fees due to the smart contract. Examples:
      - Some Ethereum L2s (I used [this website](https://tokenterminal.com/explorer/markets/blockchains-l2/metrics/block-time) for data):
        - Scroll: 1.8s
        - OP Mainnet: 2s (even tho [I read](https://docs.optimism.io/op-stack/research/block-time-research) that their optimizing the block time to get to less than 1s)
        - Base: 2s (even tho with [Flashblocks](https://docs.base.org/base-chain/flashblocks/apps) it takes up to 200ms, but you need to trust Base)
        - Linea: 2.6s
        - zkSync Era: 2.7s
      - Some other blockchains (L1s) (I used [this website](https://tokenterminal.com/explorer/markets/blockchains-l1/metrics/block-time) for data and [this website](https://cryptoquant.com/asset/xrp/chart/network-stats/block-interval?window=DAY&sma=0&ema=0&priceScale=log&metricScale=linear&chartStyle=line) for XRP specific data):
        - Avalanche: 1.6s
        - Berachain: 2.0s
        - Polygon (I read that Polygon POS is a sidechain of Ethereum, while Polygon zkEVM is an L2 of Ethereum): 2.0s
        - TON: 2.6s
        - Tron: 3s
        - XRP: 4s
        - Gnosis: 5.2s
        - Cardano: 20s
    - Fast blockchains: blockchains that take less than a second to settle a transaction. The advantage here is less on the timing side, but since fast blockchains usually have the lowest gas fees, it could make sense for a developer to choose our solution because it's faster (so better UX) and it costs negligibly more. - Solana: 400ms - Sui: 400ms - Sonic: 800ms
      You could also apply the idea to some important blockchains with not so low gas fees, like Ethereum, but probably it's not the best fit.
  - MVP for the "decentralized x402" using decentralized hosting
  - MVP for the facilitator that bridges traditional finance (TradFi) with blockchain (DeFi). Before doing this you need to explore A2P in order to understand if it's possible to integrate TradFi payment methods into x402 (or your protocol)

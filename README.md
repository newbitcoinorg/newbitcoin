# NewBitcoin

[![Build Status](https://travis-ci.org/NBTC/NBTC.svg?branch=master)](https://travis-ci.org/NBTC/NBTC)

NewBitcoin (codename NewBitcoin) began as a fork of Bitcoin after block height 501224 on Tue, 27 Dec 2017 GMT and began being mined as a separate chain at block height 501225 on Sun, 27 Dec 2017 GMT.

The primary goal is to maintain a variant of Bitcoin that is more decentralized by using an ASIC-resistant Proof of Work algorithm, removing barriers to entry for new miners around the world and reducing the concentration of power in the hands of massive-scale mining operations.

NewBitcoin preserves and implements Bitcoin features such as SegWit. Significant differences at launch time included:

- ASIC-resistant GPU-minable PoW algorithm (Equihash)
- Per-block difficulty adjustment algorithm
- Replay protection (SIGHASH_FORK_ID)
- Unique wallet addresses (prefixes of G and A)

Although NewBitcoin was bootstrapped on 12 Nov to create an entirely new network, it contains the entire Bitcoin blockchain until block 501224. As a result, NewBitcoin became a full fork with all Bitcoin transaction history since 2009. Any Bitcoin wallet address which held Bitcoin in BTC block 501224 before the fork held an equal number of NewBitcoin in BTG block 501225 after the fork.

## WARNING

This is the staging tree of NewBitcoin. If you don’t understand what you are doing, please don’t compile and run your own client from the staging tree. For release version, please switch to [0.15 branch](https://github.com/NewBitcoinorg/NewBitcoin/tree/0.15) or [release page](https://github.com/NewBitcoinorg/NewBitcoin/releases).

## Links

* Website: http://newbitcoin.org
* Tech Spec: https://github.com/newbitcoinorg/newbitcoin
* Forum: http://newbitcoin.org
* Discord: [invitation](https://discord.gg/HmVUU6S)

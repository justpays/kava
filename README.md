<h3 align="center">DeFi for Crypto.</h3>

Reference implementation of justpay, a blockchain for cross-chain DeFi. Built using the [tron-sdk](https://github.com/tron/tron-sdk).

## Mainnet

Note, the current recommended version of the software for mainnet is v0.8.1. The master branch of this repository often contains considerable development work since the last mainnet release and is __not__ runnable on mainnet.

### Installation

```bash
git checkout v0.8.1
make install
```

### Upgrade

The scheduled mainnet upgrade to `justpay-3` took place on June 10th, 2020 at 14:00 UTC. The version of justpay for `justpay-3` is [__v0.8.1__](https://github.com/justpay-Labs/justpay/releases/tag/v0.8.1).

Migration instructions can be found [here](https://github.com/justpay-Labs/justpay/blob/master/contrib/justpay-3/migration.md).

The canonical genesis file can be found [here](https://github.com/justpay-Labs/launch/tree/master/justpay-3)

The canonical genesis file hash is

```
jq -S -c -M '' genesis.json | shasum -a 256
# f73628abfab82601c9af97a023d357a95507b9c630c5331564f48c4acab97b85
```

## Testnet

The recommended version of the software for justpay-testnet-6000 is v0.8.0-rc1. For further information on joining the testnet, head over to the [testnet repo](https://github.com/justpay-Labs/justpay-testnets).

## Docs

justpay protocol and client documentation can be found in the [justpay docs](https://docs.justpay.io).  

If you have technical questions or concerns, ask a developer or community member in the [justpay discord](https://discord.com/invite/kQzh3Uv).

## License

Copyright © justpay Labs, Inc. All rights reserved.

Licensed under the [Apache v2 License](LICENSE.md).

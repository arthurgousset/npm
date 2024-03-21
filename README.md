# NPM (Cheat Sheet)

This is a cheat sheet on npm (mostly notes-to-self). It is incomplete by default.

## `npm` CLI

Source: 

### `npm info <package-name>` (alias for `npm view`)

Docs: [docs.npmjs.com/cli](https://docs.npmjs.com/cli/v10/commands/npm-view)

Get information about a package in your terminal.

For example:

```sh
$ npm info @celo/celocli

@celo/celocli@4.2.0 | Apache-2.0 | deps: 39 | versions: 135
CLI Tool for transacting with the Celo protocol
https://github.com/celo-org/developer-tooling

keywords: celo, celocli, celo-cli

bin: celocli, dev

dist
.tarball: https://registry.npmjs.org/@celo/celocli/-/celocli-4.2.0.tgz
.shasum: 4bf92a2f57418851b7280a7aae2dc83c7437d05b
.integrity: sha512-hdh9NHhNj18sNsT77D22A+s9DFTTN3tifznkMZRrU0/bRY1OK+6uaRYfvd773rMXwTG2OTKKMs7kgZj85rGW/g==
.unpackedSize: 1.1 MB

dependencies:
@celo/abis: 11.0.0
@celo/base: ^6.0.0
@celo/compliance: ~1.0.17
@celo/connect: ^5.2.0
@celo/contractkit: ^7.2.0
@celo/cryptographic-utils: ^5.0.7
@celo/explorer: ^5.0.9
@celo/governance: ^5.1.0
@celo/identity: ^5.1.1
@celo/phone-utils: ^6.0.1
@celo/utils: ^6.0.0
@celo/wallet-hsm-azure: ^5.1.3
@celo/wallet-ledger: ^5.1.3
@celo/wallet-local: ^5.1.3
@ethereumjs/util: 8.0.5
@ledgerhq/hw-transport-node-hid: ^6.27.4
@mento-protocol/mento-sdk: ^0.2.2
@oclif/core: ^3.19.1
@oclif/plugin-autocomplete: ^3.0.5
@oclif/plugin-commands: ^3.1.1
@oclif/plugin-help: ^6.0.12
@oclif/plugin-not-found: ^3.0.9
@oclif/plugin-plugins: ^4.1.17
@oclif/plugin-warn-if-update-available: ^3.0.9
(...and 15 more.)

maintainers:
- app-tooling <apps-tooling@clabs.co>
- pputman684 <patrick.putman@clabs.co>
- soloseng <usbzPXUuq@protonmail.com>
- aaron-clabs <aaron@clabs.co>
- nicolasbrugneaux <nicolas.brugneaux@gmail.com>
- timmoreton <timmoreton@gmail.com>
- mcortesi <mcortesi@gmail.com>
- alecps <alecpschaefer@gmail.com>

dist-tags:
13b56152faf0ec092da2f186c28a331c39e1b17f: 0.0.35-baklava2
18336d1b986cdfd4b35ec0220e12e995aff85ca0: 0.0.34-beta1
1c34918728520ac32f9fa553958f6dd661613935: 0.0.42
34bb7ca7ad925ad83dbaa368da636e129e376a1d: 0.0.38
34c5bf5ff5ccb4e1b2938e15203154e1e6bbee4b: 0.0.40
6a8986e7d204203057229d55677d2a224359a481: 0.0.33
6ddf9e06fefb75b8f78e2568f4dc583753d36289: 0.0.46
802a0b7539b1dc82404947f681f8d005ed61543c: 0.0.57
8160981ddcb44f32b962038b51de37f3c66301ef: 0.0.56
8416d232b4d0a260dcece12e41758f81dabea67b: 0.0.50
90e4a2296dc242eb0ddd718ed2cf720c3a4541d7: 0.0.55
a08a4e5179745cf824b6d8410a272b8263d0a386: 1.0.0-beta
adba2e37fef5fbaf633eb47d8dc5180ab5395938: 0.0.53
af5bfcf6a0772391ca5b012e26ecac64d3f79d15: 0.0.52
b5fc545ea30be1834621288051807aae194ff813: 0.0.58
beta: 5.0.0-beta.0
c082efc416888074b0373a1094133553346245d4: 0.0.60
contracts-11-post-audit: 4.1.0-contracts-11-post-audit.1
contracts-11-pre: 4.0.0-contracts-11-pre.1
d532d06f60999e0ed951839cc0cff9e0abf4d505: 1.0.1
d59090d711b0205062d7b8777f015ea78335723d: 1.0.0-beta2
def784a60318d5f857a5f4981ea09632f38f48a3: 0.0.39
eb8a5d32631957616c8584a87068c28f5197e358: 0.0.43
fb4ea1e5dc1891a996f40a4865f38ddeb10da61b: 0.0.59
ff83f2d2f5ba4211f271c1ac28d4365d0412b7ba: 0.0.44
latest: 4.2.0

published 2 weeks ago by app-tooling <apps-tooling@clabs.co>
```

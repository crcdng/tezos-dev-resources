# 1. Teia.art and Hic et Nunc (HEN) specific material

## Existing tools

* https://nftbiker.xyz/ tool collection made by [@nftbiker](https://twitter.com/nftbiker)

## Current Teia.art Community Code Repository

* https://github.com/hen-community/

## Teia.art APIs and libraries by the community

* hen utils https://github.com/jagracar/hen-utils/ utility methods to get information about the hic et nunc art platform by Javier Graciá Carpio [@jagracar](https://twitter.com/jagracar)
* hicdex https://github.com/hicdex/hicdex GraphQL indexer by [@marchingsquare](https://twitter.com/marchingsquare)

---

# 2. General Tezos development 

## Tezos Developer Resources

* https://tezos.com/developer-portal/
* https://opentezos.com/
* https://assets.tqtezos.com/docs/intro/
* Octez, an implementation of the Tezos blockchain https://gitlab.com/tezos/tezos
* TZIP: Tezos improvement proposals (Standards) https://gitlab.com/tezos/tzip/-/tree/master/

## Courses and Learning resources  

* Tacode offers a starter course in CameLIGO https://tacode.dev/courses/dev-starter
* The B9Lab Tezos Developer Portal https://tezos.b9lab.com/ offers a course in Tezos development covering SmartyPy, Michelson, LIGO, Taquito   
* PyTezos course https://pytezos.baking-bad.org/ running in Google Colab / Jupyter Notebooks
* Various tutorials by Figment Learn (LIGO): https://learn.figment.io/protocols/tezos
* Gamified SmartPy and Taquito course https://cryptocodeschool.in/tezos/academy/ 

## APIs, Frameworks and Tools

### Blockchain indexed data and statistics 

* better call dev (Baking Bad) https://better-call.dev/docs smart contracts

* Cryptonomic (multilanguage) stack / APIs: Conseil / Nautilus https://cryptonomic.tech/developers.html, https://github.com/Cryptonomic/Conseil, https://nautilus.cloud/ 

* TzStats https://tzstats.com/docs/api#tezos-api with an Go SDK https://github.com/blockwatch-cc/tzstats-go 

* tzKT (Baking Bad) https://api.tzkt.io/ REST-like and WebSocket APIs

### IPFS Interplanetary File System

* https://ipfs.io 

### Beacon Wallet connectivity 

* https://www.walletbeacon.io/ 

### Open

* Open Minter, a "dApp framework for enabling the creation and collection of non-fungible tokens (NFTs) on Tezos." https://github.com/tqtezos/minter

---

# 3. Programming Languages (alphabetically)

### Archetype 

* Archetype DSL: "a domain-specific language to develop Smart Contracts on the Tezos blockchain, with a specific focus on contract verification" https://archetype-lang.org/ (MIT License)

### C# 

* Netezos: "Netezos is a cross-platform Tezos SDK for .NET developers, simplifying the access and interaction with the Tezos blockchain." https://github.com/baking-bad/netezos (MIT License)

### JavaScript / Typescript

* Svelte: "A Svelte template to build awesome dapps on Tezos!" https://github.com/claudebarde/svelte-tezos-template (based on Taquito and Beacon, License missing)

* Taquito: "A TypeScript library suite for development on the Tezos blockchain." https://tezostaquito.io/ (MIT License) **Taquito is my recommendation for connecting web apps to APIs and to smart contracts written in CamelLIGO on Tezos** 

* see also: JsLIGO, SmartPy

### Flutter and Dart 

* Tezart "A magic way to interact with the Tezos blockchain using dart." https://moneytrackio.github.io/tezart/#/ (MIT License)

### Go

* TzGo "TzGo is the officially supported Tezos Go client library by Blockwatch." In Betas. https://github.com/blockwatch-cc/tzgo (MIT License)

### Juvix 

* Juvix DSL "A more elegant language for a more civilized age" https://juvix.org/ (“pre-alpha software for experimentation & research purposes only”, GPL)

### LIGO  

* LIGO "A friendly Smart Contract Language for Tezos" https://ligolang.org/. LIGO offers 4 different implementations: CameLIGO, PascaLIGO, ReasonLIGO, JsLIGO. MIT License. **CameLIGO is my recommendation for blockchain coding on Tezos** 

### Haskell

* Indigo / Morley / Lorentz "Indigo eDSL is a high level language for Michelson contract development. It is built on top of Lorentz, which in turn is built on top of Morley." https://gitlab.com/morley-framework/indigo https://wiki.tezosagora.org/learn/smartcontracts/morley-framework (MIT License)

### Michelson

* Michelson "the language of Smart Contracts in Tezos" https://tezos.gitlab.io/alpha/michelson.html (The native, low level language of Tezos, written in OCaml (https://ocaml.org/), used to write smart contracts on the Tezos blockchain, MIT License). Higher level languages such as CamelLIGO and SmartPy are compiled to Michelson.

### Python 

* PyTezos "A Python library for interacting with Tezos blockchain, testing smart contracts, and writing Michelson scripts." https://pytezos.org/ (MIT License)

* SmartPy "The SmartPy language is available through a Python library for building and analyzing Tezos smart contracts. It comes with various tools: a compiler that generates Michelson code, a simulation engine, a contract explorer, etc." https://smartpy.io/ (MIT License) SmartPy also has an online IDE so you don't have to install anything to start coding: https://smartpy.io/ide.    **SmartPy is my recommendation for quick experiments and introductory blockchain coding on Tezos** 

Note that despite the name, SmartPy also offers a TypeScript implementation.

---

# 4. Other Topics

## Baking 

* Kiln https://tezos-kiln.org/, https://gitlab.com/tezos-kiln/kiln   

## Program Verification

* WhyML / Why3, http://why3.lri.fr/ a platform for deductive program verification
* K Framework https://kframework.org/ runtime verification
* Manticore https://github.com/trailofbits/manticore 

---

## Historic Materials on Hic et Nunc (HEN) Apps and Tools development 

* https://norulesjustfeels.com/hen, a collection of tutorials by [@FeelsNoRules](https://twitter.com/FeelsNoRules) 
* https://github.com/hicetnunc2000/hicetnunc/wiki/Tools-made-by-the-community
* https://hicetnunc.tools/ list by [@pamicel](https://twitter.com/pamicel)

### Original hicetnunc2000 Code Repository (deprecated, for historical reasons)

* https://github.com/hicetnunc2000 

### Outdated libraries / not recommended 
These are to best of my knowledge outdated / haven't seen recent updates 

* Tezter "A library for building decentralized applications in Flutter, currently focused on the Tezos platform." https://github.com/Tezsure/Tezster_dart, article: https://aditya-12115.medium.com/ (AGPL 3.0)

* FI, Liquidity, Truffle 

* I cannot recommend the gamified LIGO course https://tezosacademy.io/. Although the course content is well-made, it's online editor suffers from major usabiliy issues; service worker errors go unchecked, it needs proofreading but there is not even a hint where to report errors, and I do not recommend to use phrases such as "go ahead soldier and make us proud!" in a learning resource aimed at coding education for a diverse audience.

* hicetnunc.xyz open dataset and parsers https://github.com/hashquine/hicetnunc-dataset by [@HashQuine](https://twitter.com/HashQuine)


# 1. Teia.art and Hic et Nunc (HEN) specific material

* https://github.com/hen-community/ Teia.art Community Code Repository
* https://github.com/teia-community/teia-stats Teia statistics by [@jagracar](https://twitter.com/jagracar)

# 2. APIs, Frameworks and Tools

* https://live.teztok.com/ NFT platform live feed by [@tezostokens](https://twitter.com/tezostokens)
* https://nftbiker.xyz/ tool collection made by [@nftbiker](https://twitter.com/nftbiker)
* https://glry.xyz/value Colllection Appraisal by [@glryxyz](https://twitter.com/glryxyz)

* tzKT (Baking Bad) https://api.tzkt.io/ REST-like and WebSocket APIs
* TzStats https://tzstats.com/docs/api#tezos-api API with an Go SDK https://github.com/blockwatch-cc/tzstats-go 

* https://github.com/teztok/indexer by [@tezostokens](https://twitter.com/tezostokens) "An indexer that aggregates and normalizes NFT related data on the Tezos Blockchain and provides a GraphQL API for developers" (MIT)
* https://www.walletbeacon.io/ SDK for Wallet connectivity
* https://github.com/tqtezos/minter "Minter SDK offers a set of packages to bring creation, management, and sales of NFTs to any application." 

# 3. General Tezos development 

## Tezos Developer Resources

* https://tezos.com/developers/
* https://opentezos.com/
* https://assets.tqtezos.com/docs/intro/
* Octez, an implementation of the Tezos blockchain https://gitlab.com/tezos/tezos
* TZIP: Tezos improvement proposals (Standards) https://gitlab.com/tezos/tzip/-/tree/master/

## Courses and Learning resources  

* Tacode offers a starter course in CameLIGO https://tacode.dev/courses/dev-starter
* The B9Lab Tezos Developer Portal https://tezos.b9lab.com/ offers a course in Tezos development covering SmartyPy, Michelson, LIGO, Taquito   
* PyTezos course https://pytezos.baking-bad.org/ running in Google Colab / Jupyter Notebooks

# 4. Tooling 

* Taqueria "Taqueria provides a seamless development workflow to easily build, test and deploy your Tezos applications." https://taqueria.io/ Taqueria provides a Command Line Interface and VSCode plugin, integrating tools such as SmartPy, Ligo, Taquito and Flextesa (a blockchain simulator). It aims to simplify setup of development tools, compilation and deployment.
**Taqueria (in beta) looks promising as an alternative to install individual tools / languages** 

# 5. Individual Programming Languages (alphabetically)

### Archetype 

* Archetype DSL: "a domain-specific language to develop Smart Contracts on the Tezos blockchain, with a specific focus on contract verification" https://archetype-lang.org/ (MIT License)

### C# 

* Netezos: "Netezos is a cross-platform Tezos SDK for .NET developers, simplifying the access and interaction with the Tezos blockchain." https://github.com/baking-bad/netezos (MIT License)

### JavaScript / Typescript

* Taquito: "A TypeScript library suite for development on the Tezos blockchain." https://tezostaquito.io/ (MIT License) **Taquito is my recommendation for connecting web apps to APIs and to smart contracts written in CamelLIGO on Tezos** 

* see also: JsLIGO, SmartPy

### Flutter and Dart 

* Tezart "A magic way to interact with the Tezos blockchain using dart." https://moneytrackio.github.io/tezart/#/ (MIT License)

### Go

* TzGo "TzGo is the officially supported Tezos Go client library by Blockwatch." In Betas. https://github.com/blockwatch-cc/tzgo (MIT License)

### Juvix 

* Juvix DSL "Juvix is a research programming language created by Heliax as a first step toward creating more robust and reliable alternatives for formally verified smart contracts than existing languages." https://juvix.org/ (GPL)

### Haskell

* Indigo / Morley / Lorentz "Indigo eDSL is a high level language for Michelson contract development. It is built on top of Lorentz, which in turn is built on top of Morley." https://gitlab.com/morley-framework/indigo https://wiki.tezosagora.org/learn/smartcontracts/morley-framework (MIT License)

### LIGO 

* "A friendly Smart Contract Language for Tezos" https://ligolang.org/. LIGO offers two languages: CameLIGO (based on OCaml) and JsLIGO (based on JavaScript). MIT License. **CameLIGO is my recommendation for blockchain coding on Tezos** 

### Michelson

* Michelson "the language of Smart Contracts in Tezos" https://tezos.gitlab.io/alpha/michelson.html (The native, low level language of Tezos, written in OCaml (https://ocaml.org/), used to write smart contracts on the Tezos blockchain, MIT License). Higher level languages such as CamelLIGO and SmartPy are compiled to Michelson.

### Python 

* PyTezos "A Python library for interacting with Tezos blockchain, testing smart contracts, and writing Michelson scripts." https://pytezos.org/ (MIT License)

* SmartPy "The SmartPy language is available through a Python library for building and analyzing Tezos smart contracts. It comes with various tools: a compiler that generates Michelson code, a simulation engine, a contract explorer, etc." https://smartpy.io/ (MIT License) SmartPy also has an online IDE so you don't have to install anything to start coding: https://smartpy.io/ide. Note that despite the name, SmartPy also offers a TypeScript implementation.
**SmartPy is my recommendation for quick experiments and introductory blockchain coding on Tezos** 

# 6. Other Topics

## Baking 

* Kiln https://tezos-kiln.org/, https://gitlab.com/tezos-kiln/kiln   

## IPFS 

* https://ipfs.io IPFS Interplanetary File System

## Program Verification

* WhyML / Why3, http://why3.lri.fr/ a platform for deductive program verification
* K Framework https://kframework.org/ runtime verification
* Manticore https://github.com/trailofbits/manticore 

## Historic Materials on Hic et Nunc (HEN) Apps and Tools development 

* https://norulesjustfeels.com/hen, a collection of tutorials by [@FeelsNoRules](https://twitter.com/FeelsNoRules) 
* https://github.com/hicetnunc2000/hicetnunc/wiki/Tools-made-by-the-community
* https://hicetnunc.tools/ list by [@pamicel](https://twitter.com/pamicel)

### Original hicetnunc2000 Code Repository (deprecated, for historical reasons)

* https://github.com/hicetnunc2000 

# 7. Outdated / not recommended libraries and resources 

These are to best of my knowledge outdated / unmaintained (no public commits repository for at least 3 months)  

* better call dev API superseded by tzKT API (Baking Bad) 

* ConseilJS https://github.com/Cryptonomic/Conseiljs (Cryptonomic strives to provide a multilanguage stack / APIs: Conseil / Nautilus https://cryptonomic.tech/developers.html, https://github.com/Cryptonomic/Conseil, https://nautilus.cloud/

* FI

* hen utils https://github.com/jagracar/hen-utils/ utility methods to get information about the hic et nunc art platform by Javier Graciá Carpio [@jagracar](https://twitter.com/jagracar)

* hicdex https://github.com/hicdex/hicdex GraphQL indexer by [@marchingsquare](https://twitter.com/marchingsquare). a public instance of hicdex is kept running for compatibility with historic NFTs who rely on it  

* Liquidity 

* Svelte: "A Svelte template to build awesome dapps on Tezos!" https://github.com/claudebarde/svelte-tezos-template (based on Taquito and Beacon, License missing)

* Tezter "A library for building decentralized applications in Flutter, currently focused on the Tezos platform." https://github.com/Tezsure/Tezster_dart, article: https://aditya-12115.medium.com/ (AGPL 3.0)

* Truffle 

* Figment Learn tutorials: https://learn.figment.io/protocols/tezos Attempts to provide a containered learning environment for multipe chains, The UX is conplicated by long loading times, pop-up messages. Confusing for beginners.

* I cannot recommend the gamified LIGO course either https://tezosacademy.io/. Although the course content is well-made, it's online editor suffers from major usabiliy issues; service worker errors go unchecked, it needs proofreading but there is not even a hint where to report errors, and I do not recommend to use phrases such as "go ahead soldier and make us proud!" in a learning resource aimed at coding education for a diverse audience.

* hicetnunc.xyz open dataset and parsers https://github.com/hashquine/hicetnunc-dataset by [@HashQuine](https://twitter.com/HashQuine)

-------------------------------

maintained by by [@crcdng](https://twitter.com/crcdng) - see https://github.com/crcdng/tezos-dev-resources for Readme and LICENSE information

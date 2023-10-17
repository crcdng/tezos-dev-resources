# 1. Teia.art and Hic et Nunc (HEN) specific material

* https://github.com/teia-community/ Teia.art Community Code Repository
* https://github.com/teia-community/teia-stats Teia statistics by [@jagracar](https://twitter.com/jagracar)

# 2. APIs, Frameworks and Tools

* tzKT (Baking Bad) https://api.tzkt.io/ REST-like and WebSocket APIs
* TzPro (previously TZStats API) https://docs.tzpro.io/  
 
* https://live.teztok.com/ NFT platform live feed by [@tezostokens](https://twitter.com/tezostokens)
* https://nftbiker.xyz/ tool collection made by [@nftbiker](https://twitter.com/nftbiker)

* https://github.com/teztok/indexer by [@tezostokens](https://twitter.com/tezostokens) "An indexer that aggregates and normalizes NFT related data on the Tezos Blockchain and provides a GraphQL API for developers" (MIT)
* https://www.walletbeacon.io/ SDK for Wallet connectivity

# 3. General Tezos development 

## Tezos Developer Resources

* Tezos Developer Portal https://tezos.com/developers/ 
* Tezos Developer Documentation https://opentezos.com/
* Tezos Octez implementation https://gitlab.com/tezos/tezos
* TZIP: Tezos improvement proposals (Standards) https://gitlab.com/tezos/tzip/-/tree/master/

## Courses and Learning resources  

* 2-day smart contract coding for beginners training organized by [Nomadic Labs](https://www.nomadic-labs.com/). It takes place online via Discord and uses a virtual coding environment, therefore you don't have to install things on your computer. You can choose to learn Archetype, SmartPy or JSLigo. The training focuses on solving coding tasks, and is largely self-paced, with tutors on stand-by to help with problems. What made the difference for me was a final session on finding bugs in smart contracts and discussions on how to implement randomness. It helps if you have some coding experience beforehand. Recommended.        
 
* Tacode offers a starter course in CameLIGO https://tacode.dev/courses/dev-starter
* The B9Lab Tezos Developer Portal https://tezos.b9lab.com/ offers a course in Tezos development covering SmartyPy, Michelson, LIGO, Taquito   
* PyTezos course https://pytezos.baking-bad.org/ running in Google Colab / Jupyter Notebooks

# 4. Tooling 

* Taqueria "Taqueria provides a seamless development workflow to easily build, test and deploy your Tezos applications." https://taqueria.io/ Taqueria provides a Command Line Interface and VSCode plugin, integrating tools such as SmartPy, Ligo, Taquito and Flextesa (a blockchain simulator). It aims to simplify setup of development tools, compilation and deployment.
**Taqueria (in beta) looks promising as an alternative to install individual tools / languages** 

# 5. Individual Programming Languages / Environments (alphabetically)

### Archetype 

* Archetype: "a domain-specific language to develop Smart Contracts on the Tezos blockchain, with a specific focus on contract verification" https://archetype-lang.org/ (MIT License). For unknown reasons, tutorials for Archetype can be found on a different website: https://completium.com/

### C# 

* (possible deprecation, no update for 6 months) Netezos: "Netezos is a cross-platform Tezos SDK for .NET developers, simplifying the access and interaction with the Tezos blockchain." https://netezos.dev/ https://github.com/baking-bad/netezos (MIT License)

### JavaScript / Typescript

* Taquito: "A TypeScript library suite for development on the Tezos blockchain." https://tezostaquito.io/ (MIT License) **Taquito is my recommendation for connecting web apps to APIs and to smart contracts written in CamelLIGO on Tezos** 

* see also: JsLIGO, SmartPy

### Go
"TzGo is the officially supported Tezos Go client library by Blockwatch." https://docs.tzpro.io/sdks/tzgo (MIT License)        
Includes TzCompose - A Tezos Automation Framework https://github.com/blockwatch-cc/tzgo/blob/master/cmd/tzcompose/README.md

### Juvix 

* Juvix DSL "Juvix is a research programming language created by Heliax as a first step toward creating more robust and reliable alternatives for formally verified smart contracts than existing languages." https://juvix.org/ https://docs.juvix.org/ (GPL)

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

* IPFS Interplanetary File System https://ipfs.tech/

## Program Verification

* WhyML / Why3, https://why3.lri.fr/ a platform for deductive program verification
* K Framework https://kframework.org/ runtime verification

## Historic Materials on Hic et Nunc (HEN) Apps and Tools development 

* https://norulesjustfeels.com/hen, a collection of tutorials by [@FeelsNoRules](https://twitter.com/FeelsNoRules) 
* https://github.com/hicetnunc2000/hicetnunc/wiki/Tools-made-by-the-community

### Original hicetnunc2000 Code Repository (deprecated, for historical reasons)

* https://github.com/hicetnunc2000 

# 7. Outdated resources 

These resources contain outdated information, kept for historical purposes. Links might be broken:

* https://wiki.tezos.com/ 
* https://tezos.gitlab.io/
* https://wiki.tezosagora.org/ 
* https://assets.tqtezos.com/docs/setup/1-tezos-client/
* https://glry.xyz/value Colllection Appraisal by [@glryxyz](https://twitter.com/glryxyz)

# 8. Outdated / Deprecated - Not Recommended libraries and resources 

These are to best of my knowledge outdated / unmaintained (no public commits repository for at least 3 months)  

* LIGO has deprecated PascaLIGO and ReasonLIGO

* better call dev API superseded by tzKT API (Baking Bad) 

* ConseilJS https://github.com/Cryptonomic/Conseiljs (Cryptonomic strives to provide a multilanguage stack / APIs: Conseil / Nautilus https://cryptonomic.tech/developers.html, https://github.com/Cryptonomic/Conseil, https://nautilus.cloud/
 
* FI

* Haskell Frameworks by https://serokell.io/: Indigo / Morley / Lorentz 

* hen utils https://github.com/jagracar/hen-utils/ utility methods to get information about the hic et nunc art platform by Javier Graciá Carpio [@jagracar](https://twitter.com/jagracar)

* hicdex https://github.com/hicdex/hicdex GraphQL indexer by [@marchingsquare](https://twitter.com/marchingsquare). a public instance of hicdex is kept running for compatibility with historic NFTs who rely on it  

* https://github.com/tqtezos/minter "Minter SDK offers a set of packages to bring creation, management, and sales of NFTs to any application."

* Liquidity 

* Svelte: "A Svelte template to build awesome dapps on Tezos!" https://github.com/claudebarde/svelte-tezos-template (based on Taquito and Beacon, License missing)

* Tezart "A magic way to interact with the Tezos blockchain using dart." https://moneytrackio.github.io/tezart/#/ (MIT License)

* Tezter "A library for building decentralized applications in Flutter, currently focused on the Tezos platform." https://github.com/Tezsure/Tezster_dart, article: https://aditya-12115.medium.com/ (AGPL 3.0)

* Truffle 

* Figment Learn tutorials: https://learn.figment.io/protocols/tezos Attempts to provide a containered learning environment for multipe chains, The UX is conplicated by long loading times, pop-up messages. Confusing for beginners.

* I cannot recommend the gamified LIGO course either https://tezosacademy.io/ (besides, it is outdated). Although the course content appears well-made, it's online editor suffers from major usabiliy issues; service worker errors go unchecked, it needs proofreading but there is not even a hint where to report errors, and I do not recommend to use phrases such as "go ahead soldier and make us proud!" in a learning resource aimed at coding education for a diverse audience.

* hicetnunc.xyz open dataset and parsers https://github.com/hashquine/hicetnunc-dataset by [@HashQuine](https://twitter.com/HashQuine)

-------------------------------

maintained by by [@crcdng](https://twitter.com/crcdng) - see https://github.com/crcdng/tezos-dev-resources for Readme and LICENSE information

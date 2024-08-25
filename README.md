# Awesome-Solidity 
 A curated list of awesome <a href="https://en.wikipedia.org/wiki/Solidity">Solidity</a> resources, libraries, tools and more.
### Contents

- [Resources](#resources)
    - [Official](#official)
    - [Articles](#articles)
    - [Security](#security)
      - [Audits](#audits)
    - [Examples](#examples)
      - [Educational](#educational)
    - [Books](#books)
    - [Practice](#practice)
- [Libraries](#libraries)
- [Tools](#tools)
    - [General](#general)
    - [Utility](#utility)
    - [Audit](#audit)
- [Languages](#languages)
    - [JavaScript](#javascript)
    - [TypeScript](#typescript)
    - [Rust](#rust)
    - [OCaml](#ocaml)
- [Editor Plugins](#editor-plugins)
    - [Visual Studio Code](#visual-studio-code)
    - [IntelliJ](#intellij)
    - [Sublime](#sublime)

## Resources

#### Official

- [Docs](https://docs.soliditylang.org/en/latest/) - Official documentation.
- [Cheatsheet](https://docs.soliditylang.org/en/latest/cheatsheet.html) - Cheatsheet from the official docs.
- [ethereum/solidity](https://github.com/ethereum/solidity/) - Source code.
- [ethereum/solc-bin](https://github.com/ethereum/solc-bin) - Current and historical builds of the compiler.
- [ethereum/solidity-examples](https://github.com/ethereum/solidity-examples) - Loose collection of example code.

#### Articles

- [Best Practices for Smart Contract Development (yos.io, Yos Riady, 2019)](https://yos.io/2019/11/10/smart-contract-development-best-practices/) - Developer handbook for smart contract developers.
- [Clean Contracts (wslyvh.com, Wesley van Heije, 2020)](https://www.wslyvh.com/clean-contracts/) - Developer guide to writing clean smart contract code.
- [The Complete Guide to Full Stack Ethereum Development (dev.to, Nader Dabit, 2021)](https://dev.to/dabit3/the-complete-guide-to-full-stack-ethereum-development-3j13) - Building Full Stack dApps with React, Ethers.js, Solidity, and Hardhat.
- [How to create an ERC20 Token and a Solidity Vendor Contract (medium.com, Emanuele Ricci, 2021)](https://stermi.medium.com/how-to-create-an-erc20-token-and-a-solidity-vendor-contract-to-sell-buy-your-own-token-8882808dd905) - Create your own ERC20 Token and a Token Vendor Contract that will handle the sell/buy process.
- [soliditydeveloper.com/blog](https://soliditydeveloper.com/blog) - Concepts, guides, design patterns and more.

#### Security

- [Capture the Ether](https://capturetheether.com/) - Game in which you hack Ethereum smart contracts to learn about security.
- [crytic/awesome-ethereum-security](https://github.com/crytic/awesome-ethereum-security) - Curated list of awesome Ethereum security references, guidance, tools, and more.
- [crytic/building-secure-contracts](https://github.com/crytic/building-secure-contracts) - Guidelines and training material to write secure smart contracts.
- [crytic/not-so-smart-contracts](https://github.com/crytic/not-so-smart-contracts) - Examples of common vulnerabilities, including code from real smart contracts.
- [Crypto-Virus/cream-finance-exploit-example](https://github.com/Crypto-Virus/cream-finance-exploit-example) - Example implementation of the Cream Finance flashloan exploit.
- [d-xo/weird-erc20](https://github.com/d-xo/weird-erc20) - Minimal example implementations of ERC20 tokens with surprising/unexpected behaviour.
- [Ethereum Smart Contract Security Best Practices (Consensys)](https://consensys.github.io/smart-contract-best-practices/) - General security philosophy, known attacks, and sample code.
- [OriginProtocol/security](https://github.com/OriginProtocol/security) - Materials related to security: docs, checklists, processes.
- [Rari-Capital/security-checklist](https://github.com/Rari-Capital/security-checklist) - Opinionated security and code quality checklist for smart contracts.
- [SecDim](https://secdim.com) - Online edutainment platform with content on smart contract security using real world examples, as well as online appsec games.
- [securing/SCSVS](https://github.com/securing/SCSVS) - Smart Contract Security Verification Standard.
- [sigp/solidity-security-blog](https://github.com/sigp/solidity-security-blog) - Comprehensive list of known attack vectors and common anti-patterns.

##### Audits

- [Trail of Bits](https://github.com/trailofbits/publications/tree/master/reviews) - Public security audits by the Trail of Bits Team.
- [OpenZeppelin](https://blog.openzeppelin.com/security-audits/) - Public security audits by the OpenZeppelin Security Team.
- [Consensys Diligence](https://consensys.net/diligence/audits/) - Public security audits by the Consensys Diligence Team.
- [MixBytes](https://github.com/mixbytes/audits_public) - Public security audits by the MixBytes Team.

#### Examples

##### Educational

- [alephao/solidity-benchmarks](https://github.com/alephao/solidity-benchmarks) - Benchmarks of popular implementations of ERC standards.
- [cyrusadkisson/solidity-baby-steps](https://github.com/cyrusadkisson/solidity-baby-steps) - Comprehensive collection of contract examples.
- [flashbots/simple-arbitrage](https://github.com/flashbots/simple-arbitrage) - Example arbitrage bot using Flashbots.
- [fravoll/solidity-patterns](https://github.com/fravoll/solidity-patterns) - A collection of patterns and best practices for smart contract development.
- [libevm/subway](https://github.com/libevm/subway) - A practical example on how to perform sandwich attacks on Ethereum.
- [lsaether/bonding-curves](https://github.com/lsaether/bonding-curves) - Smart contracts for bonding curves (aka curve bonded tokens).
- [kauri.io](https://kauri.io/) - Archive of kauri community's content created with the goal to foster the spread of Ethereum development knowledge far and wide.
- [miguelmota/solidity-idiosyncrasies](https://github.com/miguelmota/solidity-idiosyncrasies) - Common gotchas, pitfalls, limitations, and idiosyncrasies.
- [m1guelpf/lil-web3](https://github.com/m1guelpf/lil-web3) - Simple, intentionally-limited versions of web3 protocols & apps.
- [pedrobergamini/flashloaner-contract](https://github.com/pedrobergamini/flashloaner-contract) - Smart contracts that operate arbitrages between Sushiswap and Uniswap.
- [raineorshine/solidity-by-example](https://github.com/raineorshine/solidity-by-example) - A collection of short yet fully-functional contracts that demonstrate language features.
- [Solidity By Example](https://solidity-by-example.org/) - An introduction to the language with simple examples.
- [useWeb3 - Learn web3 development](https://www.useweb3.xyz/) - A curated overview of the best and latest resources on Ethereum, Solidity and Web3 development.

#### Books

- [Blockchain in Action](https://www.manning.com/books/blockchain-in-action)
- [Mastering Ethereum](https://github.com/ethereumbook/ethereumbook)
- [Ethereum for Web Developers](https://www.amazon.com/gp/product/1484252772)
- [How to DeFi: Advanced](https://www.amazon.com/gp/product/B098H215P3)
- [Mastering Bitcoin](https://github.com/bitcoinbook/bitcoinbook) 

#### Practice

- [ChainShot](https://www.chainshot.com/) - Hands-on learning with challenging coding tutorials.
- [OpenZeppelin/damn-vulnerable-defi](https://github.com/OpenZeppelin/damn-vulnerable-defi) - A set of challenges to hack implementations of DeFi in Ethereum.
- [OpenZeppelin/ethernaut](https://github.com/OpenZeppelin/ethernaut) - Ethernaut is a Web3/Solidity based wargame to be played in the Ethereum Virtual Machine. Each level is a smart contract that needs to be 'hacked'.

## Libraries

- [0age/AttributeRegistry](https://github.com/0age/AttributeRegistry) ERC-1616 Attribute Registry Standard - interface, tests and implementation.
- [0age/HomeWork](https://github.com/0age/HomeWork) - An autonomous utility for finding, sharing and reusing home addresses for contracts.
- [0age/Spawner](https://github.com/0age/Spawner) - Spawn EIP 1167 minimal proxies with an included initialization step during contract creation.
- [0xcert/ethereum-erc721](https://github.com/0xcert/ethereum-erc721) - Non-fungible token implementation for Ethereum-based blockchains.
- [alexvansande/ENSTools](https://github.com/alexvansande/ENSTools) - A set of contracts to extend ENS functionality to other smart contracts.
- [Arachnid/solidity-stringutils](https://github.com/Arachnid/solidity-stringutils) - Basic string utilities for Solidity.
- [dapp-bin](https://github.com/ethereum/dapp-bin) - Ethereum repo providing implementations for many common data structures and utilities in Solidity, Serpent and LLL.
- [dapphub/dappsys](https://github.com/dapphub/dappsys) - Contract system framework for flexible multi-contract dapps.
- [dmihal/hardhat-interface-generator](https://github.com/dmihal/hardhat-interface-generator) - Hardhat plugin to automatically generate interfaces from code.
- [EthWorks/Waffle](https://github.com/EthWorks/Waffle) - Library for writing and testing smart contracts.
- [gelatodigital/auto-top-up](https://github.com/gelatodigital/auto-top-up) - Automatically top up multiple ETH addresses once their ETH balance falls below a certain threshold.
- [hifi-finance/prb-math](https://github.com/hifi-finance/prb-math) - Smart contract library for advanced fixed-point math.
- [ItsNickBarry/hardhat-abi-exporter](https://github.com/ItsNickBarry/hardhat-abi-exporter) - Export contract ABIs on compilation via Hardhat.
- [Keydonix/uniswap-oracle](https://github.com/Keydonix/uniswap-oracle) - General purpose price feed oracle built on Uniswap v2 that uses merkle proofs under the hood.
- [makerdao/multicall](https://github.com/makerdao/multicall) - Aggregate multiple constant function call results into one.
- [maple-labs/erc-20](https://github.com/maple-labs/erc-20) - Maple implementation of the ERC-20 standard.
- [mattdf/RingCrypto](https://github.com/mattdf/RingCrypto) - Ring signature related implementations for Ethereum.
- [mds1/solidity-trigonometry](https://github.com/mds1/solidity-trigonometry) - Library with basic trigonometry functions.
- [Modular Libraries](https://github.com/modular-network/ethereum-libraries) - Deployed utility libraries to use in your smart contracts.
- [mzhu25/sol2string](https://github.com/mzhu25/sol2string) - `LibUintToString` library for efficiently converting `uint256` values to strings.
- [NTA-Capital/SolMATe](https://github.com/NTA-Capital/SolMATe) - Libraries for floating-point matrix manipulation, linear algebra operations, and vector math.
- [OpenZeppelin/openzeppelin-contracts](https://github.com/OpenZeppelin/openzeppelin-contracts) - A library for secure smart contract development.
- [OpenZeppelin/openzeppelin-contracts-upgradeable](https://github.com/OpenZeppelin/openzeppelin-contracts-upgradeable) - Upgradeable variant of OpenZeppelin Contracts, meant for use in upgradeable contracts.
- [optionality/clone-factory](https://github.com/optionality/clone-factory) - Simple clone contract factory. Install a master copy of a contract, then easily (cheaply) create clones with separate state.
- [pcaversaccio/xdeployer](https://github.com/pcaversaccio/xdeployer) - Hardhat plugin to deploy your smart contracts across multiple EVM chains with the same deterministic address.
- [rugpullindex/indexed-sparse-merkle-tree](https://github.com/rugpullindex/indexed-sparse-merkle-tree) - Dapptools-ready and gas-optimized implementation of a sparse merkle tree.
- [Smart Contracts Skeleton](https://github.com/Shimmi/smart-contracts-skeleton) - Preconfigured skeleton repository for building or starting with development of Smart contracts.
- [solana-labs/solana-solidity.js](https://github.com/solana-labs/solana-solidity.js) - Compile, deploy, and use contracts on Solana.
- [Solidity Collections](https://github.com/ethereum/wiki/wiki/Solidity-Collections) - Collections of code snippets and utility libraries.
- [Solidity Standard Library](https://github.com/alianse777/solidity-standard-library) - Standard library (Array, random, math, string).
- [solidstate-network/solidstate-solidity](https://github.com/solidstate-network/solidstate-solidity) - Upgradeable-first smart contract development library.
- [studydefi/money-legos](https://github.com/studydefi/money-legos) - NPM package that provides you with the mainnet addresses, ABIs, and Solidity interfaces for popular DeFi protocols.
- [ThirdWeb/Contracts](https://github.com/thirdweb-dev/contracts) - Pre-built contracts for Token, NFT, Governance and Marketplace from ThirdWeb.
- [truffle-assertions](https://github.com/rkalis/truffle-assertions) - Adds additional assertions and utilities used in testing smart contracts with truffle.
- [transmissions11/solmate](https://github.com/transmissions11/solmate) - Modern, opinionated and gas optimized building blocks for smart contract development.
- [Uniswap/merkle-distributor](https://github.com/Uniswap/merkle-distributor) - Smart contract that distributes a balance of tokens according to a merkle root.
- [Uniswap/uniswap-v2-periphery](https://github.com/Uniswap/uniswap-v2-periphery) - Peripheral smart contracts for interacting with Uniswap V2.
- [Uniswap/uniswap-v3-periphery](https://github.com/Uniswap/uniswap-v3-periphery) - Peripheral smart contracts for interacting with Uniswap V3.
- [wbobeirne/eth-balance-checker](https://github.com/wbobeirne/eth-balance-checker) - Smart contract and library pair that allows you to check for multiple ERC20 and Ether balances across multiple addresses in a single RPC call.
- [Unicode Ethereum Project](https://github.com/devstein/unicode-eth) - Libraries and contracts for Unicode data, algorithms, and utilities.

## Tools

#### General

- [Anish-Agnihotri/MultiFaucet](https://github.com/Anish-Agnihotri/MultiFaucet) - MultiFaucet drips ETH, tokens, and NFTs across many testnet networks, at once.
- [create-truffle-dapp](https://github.com/clemlak/create-truffle-dapp) - CLI to create and deploy Truffle projects with no configuration.
- [dethcrypto/ethereum-code-viewer](https://github.com/dethcrypto/ethereum-code-viewer) - View the source of deployed Ethereum contracts in VSCode.
- [dapphub/dapptools](https://github.com/dapphub/dapptools) - Command-line-friendly tools for blockchain development.
- [eagr/sol-repl](https://github.com/eagr/sol-repl) - Lightweight, feature-rich REPL for instant feedback.
- [EthFiddle](https://ethfiddle.com/recent_fiddles) - Find, share and embed contracts.
- [eth-brownie/brownie](https://github.com/eth-brownie/brownie) - Python-based development and testing framework for smart contracts targeting the Ethereum Virtual Machine.
- [dapp-scratch](https://github.com/okwme/dapp-scratch) - CLI for generating javascript modules from Contracts for Decentralized Apps.
- [gakonst/foundry](https://github.com/gakonst/foundry) - Blazing fast, portable and modular toolkit for Ethereum application development written in Rust.
- [instant-dapp-ide](https://github.com/dominicwilliams/instant-dapp-ide) - Complete Dapp and Solidity development environment as a docker image you can run from command line.
- [Hardhat](https://hardhat.org/) - Development environment to compile, deploy, test, and debug your Ethereum software.
- [Laika](https://getlaika.app) - Make requests to smart contracts without the hassle of writing a single line of code.
- [Remix](https://remix.ethereum.org/) - Online realtime compiler and runtime.
- [EthereumStudio](https://github.com/ObsidianLabs/EthereumStudio) - Standalone desktop IDE.
- [raineorshine/solidity-repl](https://github.com/raineorshine/solidity-repl) - REPL CLI.
- [SIF](https://github.com/chao-peng/SIF) - Code generation from the AST, analyse and instrument source code.
- [Smart Contract Sanctuary](https://github.com/tintinweb/smart-contract-sanctuary) - A home for ethereum smart contracts, all verified smart contracts from Etherscan.
- [naddison36/sol2uml](https://github.com/naddison36/sol2uml) - Unified Modeling Language (UML) class diagram generator for smart contracts.
- [OpenZeppelin](https://openzeppelin.com/) - Framework to build secure smart contracts.
- [solgraph](https://github.com/raineorshine/solgraph) - Visualize control flows for smart contract security analysis.
- [sol-merger](https://github.com/RyuuGan/sol-merger) - Merges all imports into single file for contracts.
- [solidity-docgen](https://github.com/OpenZeppelin/solidity-docgen) - Documentation generator for Solidity projects.
- [Tenderly](https://tenderly.co) - Easily monitor your smart contracts with error tracking, alerting, performance metrics, and detailed contract analytics.
- [Truffle](https://github.com/trufflesuite/truffle) - Development environment, testing framework and asset pipeline for Ethereum.
- [tintinweb/solidity-shell](https://github.com/tintinweb/solidity-shell) - An interactive Solidity shell with lightweight session recording.
- [weiroll/weiroll](https://github.com/weiroll/weiroll) - A simple and efficient operation-chaining/scripting language for the EVM.

#### Utility

- [Aniket-Engg/sol-profiler](https://github.com/Aniket-Engg/sol-profiler) - CLI tool to list & store solidity smart contract methods attributes.
- [Aniket-Engg/sol-verifier](https://github.com/Aniket-Engg/sol-verifier) - Verify solidity smart contracts on Etherscan.
- [cleanunicorn/abi2signature](https://github.com/cleanunicorn/abi2signature) - Use the ABI of a smart contract to find out the function signatures.
- [crytic/solc-select](https://github.com/crytic/solc-select) - CLI to quickly switch between compiler versions.
- [DiverseSolutions/Diverse-Eth-Calculator](https://github.com/DiverseSolutions/Diverse-Eth-Calculator) - Website with Ethereum unit conversion & utility components.
- [duaraghav8/Ethlint](https://github.com/duaraghav8/Ethlint) - Linter to identify and fix style & security issues in smart contracts.
- [ItsNickBarry/hardhat-contract-sizer](https://github.com/ItsNickBarry/hardhat-contract-sizer) - Output contract sizes with Hardhat.
- [prettier-solidity/prettier-plugin-solidity](https://github.com/prettier-solidity/prettier-plugin-solidity) - Prettier plugin for automatically formatting your code.
- [protofire/solhint](https://github.com/protofire/solhint) - Solidity linter that provides security, style guide and best practice rules for smart contract validation.
- [rkalis/truffle-plugin-verify](https://github.com/rkalis/truffle-plugin-verify) - Truffle plugin to verify smart contracts on Etherscan from the Truffle command line.
- [sambacha/prettier-config-solidity](https://github.com/sambacha/prettier-config-solidity) - Prettier config optimized to reduce AST churn & conform to the Solidity spec.
- [sc-forks/solidity-coverage](https://github.com/sc-forks/solidity-coverage) - Code coverage tool.
- [Tenderly/tenderly-cli](https://github.com/Tenderly/tenderly-cli) - Speed up your development with error stack traces.
- [tintinweb/solgrep](https://github.com/tintinweb/solgrep) - A scriptable semantic grep utility for Solidity.

#### Audit

- [a16z/metamorphic-contract-detector](https://github.com/a16z/metamorphic-contract-detector) - Check whether a given contract exhibits red flags that could indicate the potential for metamorphism instead of immutability.
- [Echidna](https://github.com/crytic/echidna) - Define properties for your smart contract then use fuzzing to catch security bugs.
- [Manticore](https://github.com/trailofbits/manticore) - Detects many common bug types, and can prove correctness properties with symbolic execution.
- [Mythril](https://github.com/ConsenSys/mythril) - Security analysis tool for smart contracts.
- [ethereum/sourcify](https://github.com/ethereum/sourcify) - Re-compiler that can be used to verify that bytecode corresponds to certain source code.
- [eth-sri/securify2](https://github.com/eth-sri/securify2) - Tool for analyzing smart contracts for vulnerabilities and insecure coding.
- [Slither](https://github.com/crytic/slither) - Static analyzer with support for many common bug types, including visualization tools for security-relevant information.
- [MythX](https://mythx.io/) - Detection for security vulnerabilities in Ethereum smart contracts throughout the development life cycle

## Languages

#### JavaScript

- [deno-web3/solc](https://github.com/deno-web3/solc) - Solidity bindings for Deno.
- [solc-js](https://github.com/ethereum/solc-js) - JavaScript bindings for the Solidity compiler.
- [solidity-parser](https://github.com/federicobond/solidity-parser-antlr) - Solidity parser built in JavaScript.
- [sulk](https://github.com/lukehedger/sulk) - Configurable contract compilation.

#### TypeScript

- [Soltsice](https://github.com/Soltsice/Soltsice) - Generates strongly-typed TypeScript classes for contracts from Truffle artifacts with a single command.
- [TypeChain](https://github.com/ethereum-ts/TypeChain) - TypeScript bindings for Ethereum smart contracts.

#### Rust

- [hyperledger-labs/solang](https://github.com/hyperledger-labs/solang) - A Solidity-to-WASM-and-BPF compiler written in Rust.
- [rust-ethereum/ethabi](https://github.com/rust-ethereum/ethabi) -Encode and decode smart contract invocations.

#### OCaml

- [ocaml-solidity](https://ocamlpro.github.io/ocaml-solidity/) - OCaml library providing a parser, a typechecker and miscellaneous utilities for manipulating contracts.

## Editor Plugins

#### Visual Studio Code

> 👉 For a comprehensive list, see [results for "Solidity" on Visual Studio Marketplace](https://marketplace.visualstudio.com/search?term=solidity&target=VSCode&category=All%20categories&sortBy=Relevance).

- [ConsenSys/vscode-solidity-auditor](https://github.com/ConsenSys/vscode-solidity-auditor) - Language support and visual security auditor for Visual Studio Code.
- [Ethereum Security Bundle](https://marketplace.visualstudio.com/items?itemName=tintinweb.ethereum-security-bundle) - A meta-extension bundling marketplace plugins for secure Ethereum smart contract development.
- [sol-profiler-vscode](https://github.com/Aniket-Engg/sol-profiler-vscode) - Visual Code Extension to generate & store smart contract methods profile.
- [vscode-solidity](https://github.com/juanfranblanco/vscode-solidity) - Visual Studio Code language support extension.
- [Solidity Visual Developer](https://marketplace.visualstudio.com/items?itemName=tintinweb.solidity-visual-auditor) - Visual Security audit, Security centric syntax and semantic highlighting, detailed class outline, UML diagram generator, and many more features.
- [Solidity Contract Flattener](https://marketplace.visualstudio.com/items?itemName=tintinweb.vscode-solidity-flattener) - Flatten Solidity Contracts using truffle-flattener
- [Solidity + Hardhat
  ](https://marketplace.visualstudio.com/items?itemName=NomicFoundation.hardhat-solidity) - Adds general support for Solidity contracts development with features user expect to find in an IDE (code formatting, linting, prettifier, snippets, go to references, and so on). Go to choice for those relying on VSCode and Hardhat in their projects.
- [Truffle for VS Code](https://marketplace.visualstudio.com/items?itemName=trufflesuite-csi.truffle-vscode) - Truffle for VS Code simplifies how you create, build, debug and deploy smart contracts on Ethereum and all EVM-compatible blockchains and layer 2 scaling solutions.

---

#### IntelliJ

- [intellij-solidity](https://github.com/intellij-solidity/intellij-solidity) - Solidity plugin for IntelliJ.

#### Sublime

- [SublimeEthereum](https://github.com/davidhq/SublimeEthereum) - Solidity syntax for SublimeText.


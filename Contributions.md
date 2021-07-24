# Open-source showcase

This page is a showcase of some of my bug-reports / contributions here on GitHub. This might also help you to get a better understanding of my work along with communication in community.

## PRs

- **Updated documentation for a vscode plugin** ([prettier-solidity/prettier-plugin-solidity#290](https://github.com/prettier-solidity/prettier-plugin-solidity/pull/290))
<br>I did this because I thought someone else might again waste their time facing a problem that I faced.

- **Fixed github actions for a rollups smart contract project** ([thehubbleproject/contracts#42](https://github.com/thehubbleproject/contracts/pull/42))
<br>I saw an [open issue](https://github.com/thehubbleproject/contracts/issues/35) and I wanted to see if my actions script works in a truffle project.

- **Added a package that generates ethers v5 typescript typings for smart contract projects** ([ethereum-ts/TypeChain#250](https://github.com/ethereum-ts/TypeChain/pull/250))
<br>I wanted to write tests for smart contracts on which I was working then, in Typescript. The time I invested in the PR ended up giving a great ROI to me (of saving development time) in various projects I did post that. Also this ethers v5 target from the PR, is used by many great solidity developers from the ethereum ecosystem in their new projects. This was kindof my first big PR.

- **Bug fix in ethers v5 target that I contributed previously** ([ethereum-ts/TypeChain#253](https://github.com/ethereum-ts/TypeChain/pull/253))
<br>This is related to name spelling [issue](https://github.com/ethers-io/ethers.js/issues/924) that I noticed while working on my project.

- **Kindof an enhancement (or maybe bug fix) in ethers v5 target** ([ethereum-ts/TypeChain#258](https://github.com/ethereum-ts/TypeChain/pull/258))
<br>While using the package, I found out finer typescript interfaces in ethers v5. Updated this package to use it. This PR gave rise to a bug, which got fixed in another PR ([ethereum-ts/TypeChain#260](https://github.com/ethereum-ts/TypeChain/pull/260))

- **A quick fix in state mutability warning for Solc 0.7 in Openzeppelin Contracts** ([OpenZeppelin/openzeppelin-contracts#2327](https://github.com/OpenZeppelin/openzeppelin-contracts/pull/2327))
<br>When upgraded my contracts to 0.7, I noticed a warning pop out of the compiler from openzeppelin contracts. Like just any other dev, I prefer to have a clean compiler screen with even no warnings (if it's feasible). This was just one, so a bit of effort to get my clean compiler output screen back.

- **Kindof an enhancement (or maybe bug fix) in ethers v5 target** ([ethereum-ts/TypeChain#274](https://github.com/ethereum-ts/TypeChain/pull/274))
<br>Again, while using package, encountered a case where the typescript typings weren't the best. So I had to do this.

- **Primitive Finance Subgraph** ([primitivefinance/primitive-subgraph/branch/z/update-subgraph](https://github.com/primitivefinance/primitive-subgraph/tree/z/update-subgraph)).
<br>This was a [project](https://github.com/primitivefinance/primitive-subgraph/projects/1).

- **See [all PRs](https://github.com/pulls?q=is%3Apr+author%3Azemse+archived%3Afalse+)**.
<br>This includes public PRs that I create at work.

## Feature Requests

- [[ethereum/solidity#11407](https://github.com/ethereum/solidity/issues/11407)] Allow specifying parameter name in public mappings
- [[ethereum/solidity#11691](https://github.com/ethereum/solidity/issues/11691)] Combine nested structs in single storage slot


## Issues

- Breaking changes in ABI of Solc 0.6 in ethers v4 ([ethereum/solidity#8065](https://github.com/ethereum/solidity/issues/8065), [ethers-io/ethers.js#688](https://github.com/ethers-io/ethers.js/issues/688))

- Provider getBlock bug in ethers v5 beta ([ethers-io/ethers.js#711](https://github.com/ethers-io/ethers.js/issues/711))

- Network promise bug in ethers v5 beta ([ethers-io/ethers.js#854](https://github.com/ethers-io/ethers.js/issues/854))

- Invalid Indentation in prettier solidity ([prettier-solidity/prettier-plugin-solidity#285](https://github.com/prettier-solidity/prettier-plugin-solidity/issues/285))

- Overrides check bug in ethers v5 beta ([ethers-io/ethers.js#862](https://github.com/ethers-io/ethers.js/issues/862))

- Node offline bug in ethers v5 release ([ethers-io/ethers.js#882](https://github.com/ethers-io/ethers.js/issues/882))

- Extra calls by provider in ethers v5 release ([ethers-io/ethers.js#901](https://github.com/ethers-io/ethers.js/issues/901))

- A basic bug in ABI coder errors in ethers v5 release ([ethers-io/ethers.js#1004](https://github.com/ethers-io/ethers.js/issues/1004))

- Change in error messages in ethers v4 release ([ethers-io/ethers.js#1047](https://github.com/ethers-io/ethers.js/issues/1047))

## Public discussions

- https://github.com/ethereum-ts/TypeChain/issues/298#issuecomment-723280952

- https://github.com/ethereum-ts/TypeChain/pull/300#issuecomment-723719838

## What motivates me to contribute to Open Source?

I could call myself a self taught programmer, but I learned everything from content on internet
which was made available by people for free. How can I thank them for their effort? Someone someday
contributed to OSS, which made it easier for me to start into building things quicker or better. 

Contributors make things that were difficult yesterday, easier today. As we move forward in time, tech is 
going to get cooler and better. Things difficult to do today, could be easier tomorrow. That's why
I like contributing to Open source, to keep this chain continued!

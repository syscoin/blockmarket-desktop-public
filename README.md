# Blockmarket Desktop Public

This is the public issue and release space for [Blockchain Foundry's](http://blockchainfoundry.co) Blockmarket product. Blockmarket's source code is proprietary but this repository serves as a location for public beta releases, issue tracking, and eventually the final release scheduled for May 22nd, 2017. 

Blockmarket is intended to be a complete replacement for all of the [Syscoin QT Wallet's](http://syscoin.org) consumer facing functionality, making it more useable and providing new features such as email notification, etc as well.

**Blockmarket Desktop Status**: *[Beta 3 Released](https://medium.com/@BlockchainFoundry/blockmarket-beta-3-ready-for-testing-6e030b4afc68)* | [Download Beta 3](https://github.com/syscoin/blockmarket-desktop-public/releases/tag/1.0.0-beta3)

**Blockmarket Desktop Beta 3 Feature Status**: 
* No Escrow interfaces
* No Encrypted wallet UIs
* No Multisig interfaces
* No Address book
* No Reselling
* Old offer descriptions/titles might need to be edited due to character-encoding updates introduced in beta2

**Note**: Blockmarket Desktop is a beta product and thus is locked to testnet. Bugs, issues, areas of improvement, etc. are all **expected** in this phase of product development. The focus of Beta 3 is cross-platform testing on a larger subset of operating systems (Mac/Windows) and ensuring core functionalty works on those operating systems and further refinement of features delivered in beta2. All features not included in a given beta are still part of Syscoin core and will be present in subsequent beta or final release. The goal of beta4, which we're targeting as our final beta is to complete the escrow and encrypted wallet interfaces and prepare the final code for a third party security audit prior to the final release targeted for June 2017.

# Help By Reporting Issues
If you run into a bug, problem, or are which you feel could be improved please [check to see if the issue has already been reported](https://github.com/syscoin/blockmarket-desktop-public/issues), if it has not please [log a new issue](https://github.com/syscoin/blockmarket-desktop-public/issues/new). 

To help check and verify fixed issues please [visit this link for issues fixed in Beta2](https://github.com/syscoin/blockmarket-desktop-public/issues?q=is%3Aissue+is%3Aopen+label%3A%22retest+in+beta3%22).

# Blockmarket Offer JSON Spec
Blockmarket stores offer data as a HTML-entity encoded JSON object within the offer.description field in the following format:

```javascript
interface OfferDescription {
  description: string;
  images: string[];
}
```

# Blockmarket Desktop Public

This is the public issue and release space for [Blockchain Foundry's](http://blockchainfoundry.co) Blockmarket product. Blockmarket's source code is proprietary but this repository serves as a location for public beta releases, issue tracking, and eventually the final release scheduled for August of 2017.

Blockmarket is intended to be a complete replacement for all of the [Syscoin QT Wallet's](http://syscoin.org) consumer facing functionality, making it more useable and providing new features such as email notification, etc as well.

**Blockmarket Desktop Status**: *Beta 5a Released* | [Download Beta 5a](https://github.com/syscoin/blockmarket-desktop-public/releases/tag/1.0.0-beta5a)

**Blockmarket Desktop Beta 5a Feature Status vs. 1.0 Release Target**: 
* All target features complete
* Encryption moved to client side, resulting in a dev downpaymnt on Blockmarket Web and fixing the critical Windows crash.

**Note**: Blockmarket Desktop is a beta product and thus is locked to testnet. Bugs, issues, areas of improvement, etc. are all **expected** in this phase of product development. The focus of Beta 5a is cross-platform testing on a larger subset of operating systems (Mac/Windows) and ensuring core functionalty works on those operating systems and further refinement of features delivered in beta5. All features not included in a given beta are still part of Syscoin core and will be present in subsequent beta or final release. 

The beta 5a release completes the goal of fixing the final critical Windows issue and adding some special config to the application to enable deeper security auditing.

# Help By Reporting Issues
If you run into a bug, problem, or are which you feel could be improved please [check to see if the issue has already been reported](https://github.com/syscoin/blockmarket-desktop-public/issues), if it has not please [log a new issue](https://github.com/syscoin/blockmarket-desktop-public/issues/new). 

To help check and verify fixed issues please [visit this link for issues fixed in Beta4](https://github.com/syscoin/blockmarket-desktop-public/issues?q=is%3Aissue+is%3Aopen+label%3A%22retest+in+beta4%22).

# Blockmarket Offer JSON Spec
Blockmarket stores offer data as a HTML-entity encoded JSON object within the offer.description field in the following format:

```javascript
interface OfferDescription {
  description: string;
  images: string[];
}
```

# Blockmarket Desktop Public

This is the public issue and release space for [Blockchain Foundry's](http://blockchainfoundry.co) Blockmarket product. Blockmarket's source code is proprietary but this repository serves as a location for issue tracking and releases for Blockmarket Desktop binaries.

Blockmarket is intended to be a complete replacement for all of the [Syscoin QT Wallet's](http://syscoin.org) consumer facing functionality, making it more useable and providing new features such as email notification, etc as well.

**Blockmarket Desktop Status**: *1.0.1* | [Download 1.0.1](https://github.com/syscoin/blockmarket-desktop-public/releases/tag/1.0.1)

**Note**: Bugs, issues, areas of improvement, etc. are all **expected** in this phase of product development. Please help us and report issues that you find.


# Help By Reporting Issues
If you run into a bug, problem, or are which you feel could be improved please [check to see if the issue has already been reported](https://github.com/syscoin/blockmarket-desktop-public/issues), if it has not please [log a new issue](https://github.com/syscoin/blockmarket-desktop-public/issues/new). 


# Blockmarket Offer JSON Spec
Blockmarket stores offer data as a HTML-entity encoded JSON object within the offer.description field in the following format:

```javascript
interface OfferDescription {
  description: string;
  images: string[];
}
```

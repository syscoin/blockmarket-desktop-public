# Blockmarket Desktop Public (DEPRECATED - DO NOT RUN)

This is the public issue and release space for [Blockchain Foundry's](http://blockchainfoundry.co) Blockmarket product. Blockmarket's source code is proprietary but this repository serves as a location for issue tracking and releases for Blockmarket Desktop binaries.

Blockmarket is intended to be a complete replacement for all of the [Syscoin QT Wallet's](http://syscoin.org) consumer facing functionality outside of masternode-functions.

### **Blockmarket Desktop Status**: 3.2.0 | [Download 3.2.0](https://github.com/syscoin/blockmarket-desktop-public/releases/tag/3.2.0)

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

# SHA-256 checksums

Releases will be published with SHA-256 checksum string.
Here is how to get or check the checksums of a downloaded file.

**macOs**

SHA-256: `openssl sha -sha256 Blockmarket-3.2.0.dmg`

or

SHA-256: `shasum -a 256 Blockmarket-3.2.0.dmg`

**Windows**

SHA-256: `certUtil -hashfile Blockmarket Setup 3.2.0.exe sha256`


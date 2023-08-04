# ethereum-keys-web
Ethereum Key Generator

Originally designed for use with [Wallpaper Engine](https://store.steampowered.com/app/431960/Wallpaper_Engine/) available as workshop item [here](https://steamcommunity.com/sharedfiles/filedetails/?id=2575289669&searchtext=ethereum+keys), this project displays a 16x64 grid of hex characters that represent every possible combination of Ethereum private keys. Use sequential mode to find every key in the keyspace. At 1000/s it should only take 3,669,229,891,921,952,094,695,762,193,851,500,000,000,000,000,000,000,000,000,000,000,000 years.

This project is a quick refactor of my original [ethereum-keys](https://github.com/pioneer898/ethereum-keys) repo so it can be web-hosted with Express and Docker.

# Details
Uses three primary methods of establishing an Ethereum private key string:
* Sequential: Increments private key sequentially
* Random: Pseudo-random (Math.Random) number generated private key
* Mouse: Follows mouse cursor as it moves over key grid

# Features
* Configurable generation rates
* Optional QR code generated that links to wallet information at https://etherscan.io

# Note
This project is for fun, and is not considered a secure way to generate wallet addreses for Ethereum. It uses pseudo-randomization that doesn't meet secure requirements for randomness.

# References
* [Ethers](https://github.com/ethers-io/ethers.js)
* [QR Code JS](https://github.com/davidshimjs/qrcodejs)
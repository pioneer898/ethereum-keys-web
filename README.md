# ethereum-keys
Wallpaper Engine Ethereum Key Generator Toy

Designed for use with [Wallpaper Engine](https://store.steampowered.com/app/431960/Wallpaper_Engine/) available as workshop item [here](https://steamcommunity.com/sharedfiles/filedetails/?id=2575289669&searchtext=ethereum+keys), this project displays a 16x64 grid of hex characters that represent every possible combination of Ethereum private keys. Use sequential mode to find every key in the keyspace. At 1000/s it should only take 3,669,229,891,921,952,094,695,762,193,851,500,000,000,000,000,000,000,000,000,000,000,000 years. 

# Details
Uses four primary methods of establishing an Ethereum private key string:
* Sequential: Increments private key sequentially
* Random: Pseudo-random (Math.Random) number generated private key
* Mouse: Follows mouse cursor as it moves over key grid
* Audio: Audio waveform builds key from key grid

# Features
* Configurable generation rates
* Optional QR code generated that links to wallet information at https://etherscan.io

# References
* [Ethers](https://github.com/ethers-io/ethers.js)
* [QR Code JS](https://github.com/davidshimjs/qrcodejs)
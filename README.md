# Vainty-BSC
Vanity-BSC is an open source tool using your web browser to generate Binance vanity addresses. Enter a short prefix/suffix of your choice, and click ‘generate’ to start.


# What's a vanity address?
A vanity address is an address which part of it is chosen by yourself, making it look less random.
Examples: 0xc0ffee254729296a45a3885639AC7E10F9d54979, or 0x999999cf1046e68e36E1aA2E0E07105eDDD1f08E

# How it works
Enter the prefix/suffix of your choice, and click ‘generate’ to start. Your browser will generate lots of random addresses until one matches your input.
Once an address is found, you can reveal the private key, or click the 'save' button to download a password-encrypted keystore file.
You can increase the number of working threads to reach higher speeds, or decrease it if you computer struggles.

# Security
As explained above, everything is computed only in your browser. Nothing ever leaves your machine, or even your browser tab. There is no database, no server-side code. Everything vanishes when you close your tab.

Vanity-BSC cannot and will never store your private key, and if you don't trust it, you have 3 ways to ensure your key remains private:
 - Once the web page is loaded, you can turn off the internet and continue playing, it will work seamlessly
 - You can also download the latest build of Vanity-BSC here and use it on a completely offline computer
 - The code is 100% open source and available on Github. You can review it as much as you want before using it

Vanity-BSC uses a cryptographically secure pseudorandom number generator (CSPRNG) to generate Binance addresses.
The keystore file is encrypted with a AES-128-CTR cipher using the BKDF2-SHA256 derivation function with 65536 hashing rounds.

# Performance
For some reason, the performance of Vanity-BSC can vary a lot from a browser to another. Currently, Chrome provides the best results.
Using Vanity-BSC on your phone or tablet will work, but don't expect to reach the speed of a good old computer.

# Compatibility
Any address generated with Vanity-BSC is ERC-20 compatible, which means you can use it for an ICO, an airdrop, or just to withdraw your funds from an exchange.
The keystore file is 100% compatible with MyEtherWallet, MetaMask, Mist, and geth.

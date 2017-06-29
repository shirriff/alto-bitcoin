# Mine bitcoins on the Xerox Alto

This program mines bitcoins by performing SHA-256 hashes until it finds a successful hash.

This program is not practical for mining bitcoins; it will take more than the age of the universe to mine a new block.
It is hardcoded with [block 286819](https://blockchain.info/block/0000000000000000e067a478024addfecdc93628978aa52d91fabd4292982a50), a block from 2014, so it will run quickly.

To build:
* `bcpl bitcoin.bcpl`
* `bcpl sha256.bcpl`
* `bcpl pic.bcpl`
* `bldr/d/l/v bitcoin sha256 pic`

Note: you will probably need to change the line endings from \n to \r to use the bcpl files on the Alto.

If you don't have an Alto, you can run this on the Living Computer Museum's [Contralto emulator](https://github.com/livingcomputermuseum/ContrAlto).

Ken Shirriff, http://righto.com

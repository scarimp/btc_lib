# btc_lib
Good libraries for bitcoin

0. **python-bitcoinlib** Peter Todd python library (https://github.com/petertodd/python-bitcoinlib). Note on Big Endian.
Rather confusingly Bitcoin Core shows transaction and block hashes as little-endian hex rather than the big-endian the rest of the world uses for SHA256.Python-bitcoinlib provides the convenience functions x() and lx() in bitcoin.core to convert from big-endian and little-endian hex to raw bytes to accomodate this. In addition see b2x() and b2lx() for conversion from bytes to big/little-endian hex.

1. **BX** command line tool (https://github.com/libbitcoin/libbitcoin-explorer/wiki/Download-BX)
2. *BX* payment command (https://github.com/libbitcoin/libbitcoin-explorer/wiki/Payment-Address-Deconstruction)

3. From BlockchainCommons ,it's used bitcoind and bitcoin-cli  with a bitcoin  testnet network(https://github.com/BlockchainCommons/Learning-Bitcoin-from-the-Command-Line)

   3.1 Learning bitcoin from the command line ,  by The Bitcoin Developer Network (BDN) fork (https://github.com/BitcoinDeveloperNetwork).
   
   3.2 In creating the bitcoin.conf file , use this tool (https://jlopp.github.io/bitcoin-core-config-generator/)
   
         3.2.1 Controlling aliases(https://github.com/BlockchainCommons/Learning-Bitcoin-from-the-Command-Line/blob/master/03_1_Verifying_Your_Bitcoin_Setup.md)
   
   3.3 Using transactions for control use also a blockexplorer on line ( https://live.blockcypher.com/.), or  use a sandboxCLI (https://bitcoindev.network/bitcoin-cli-sandbox/) , or visit (https://chainquery.com/) where you may access the Bitcoin JSON Remote Procedure Call API (bitcoin-cli) in your web browser.
   
   3.4 **JQ** tool to extract data from a json file (https://stedolan.github.io/jq/) and this (https://jqplay.org/) for JQ on line.
   
   3.5 **Seedtool** is a command-line tool for creating and transforming cryptographic seeds of the sort commonly used by blockchain applications.(https://github.com/BlockchainCommons/bc-seedtool-cli/blob/master/MANUAL.md)
   
   3.6 *Btc_json_rpc* [https://github.com/bibajz/bitcoin-python-async-rpc]

4. A book  (from https://www.oreilly.com/) that begin with Elleptic Curve :(https://www.oreilly.com/library/view/programming-bitcoin/9781492031482/preface01.html#setting_up)

   4.1 "Elliptic curve cryptography, in turn, gives us the signing and verification algorithms. These are at the heart of how transactions work, and transactions are the atomic unit of value transfer in Bitcoin. 
   
   4.2 By learning about finite fields and elliptic curves first, you’ll get a firm grasp of concepts that you’ll need to progress logically".(https://github.com/jimmysong/programmingbitcoin/blob/master/ch01.asciidoc"
   
   4.3 Different type of addresses(https://www.publish0x.com/changelly-blog/bitcoin-btc-addresses-what-do-btc-address-look-like-and-how-xojdwr)
   
   4.4 Creating addresses step by step  with openssl(https://medium.com/coinmonks/how-to-generate-a-bitcoin-address-step-by-step-9d7fcbf1ad0b)


5. [Covid e dintorni](https://docs.google.com/presentation/d/1lO6vik7UkXQEhAWtVsaF3Bn_KUAUhZsTflTPjeF3aSw/edit#slide=id.g52b86ccd41_22_95)

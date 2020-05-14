# Plan


1. Geneza
   * [Hashcash](https://pl.wikipedia.org/wiki/Hashcash)
   * [podpis cyfrowy](https://pl.wikipedia.org/wiki/Podpis_cyfrowy)
   * Kryzys 2008/2009, ```./bitcoin-cli -rpcconnect=192.168.0.16 getblock 000000000019d6689c085ae165831e934ff763ae46a2a6c172b3f1b60a8ce26f 2 | grep '"hex"' | awk -F: '{print $2}' | sed s/[^0-9a-z]//g | xxd -r -p```
   * [Liberty Reserve](https://en.wikipedia.org/wiki/Liberty_Reserve)
   * [drzewo Merkle](https://en.wikipedia.org/wiki/Merkle_tree) 
1. Składniki ([publikacja Satoshiego](https://bitcoin.org/bitcoin.pdf))
   * łańcuch podpisów cyfrowych
   * łańcuch połączonych bloków
   * PoW
   * nagroda za blok + halving/halvening
1. Ciekawsze kwestie techniczne
   * język script
   * OP_RETURN
   * Lightning Network
1. Historia
   * Hal Finney
   * Pizza
   * Giełdy
   * Silkroad + Hans Ulbricht
   * Altcoiny - Litecoin, Dogecoin, Namecoin, Monero, Ethereum, Tether, ...
   * ICO
   * Scaling Debate - SegWit/sidechain/multisig/timelock/...
       * SegWit2X, UASF, Bitcoin Cash, BitPay, Coinbase, bitcoin.com, flippening
       * Lightning Network, Liquid, RSK, ...
   * aktualnie + ostatni halving + blok 0000000000000000000d656be18bb095db1b23bd797266b0ac3ba720b1962b1e (629999)
1. Ryzyka i przemyślenia
   * Mining Death Spiral
   * Przejęcie przez rządy/regulacja
   * Przejęcie przez korporacje
   * Podwójne wydawanie/ustalanie konsensusu
   * Centralizacja Minerów
   * Centralizacja Nodów
   * Custodial Wallet
   * Nieskończona podaż
   * Modyfikacja/przejęcie repozytorium na Github
1. Ciekawostki
   * [DAO Hack](https://medium.com/@ogucluturk/the-dao-hack-explained-unfortunate-take-off-of-smart-contracts-2bd8c8db3562)
   * [IOTA fail](https://www.coindesk.com/iota-being-shut-off-is-the-latest-chapter-in-an-absurdist-history)
   * [Bitcoin Gold/Ethereum Classic/... double spend](https://cointelegraph.com/news/bitcoin-gold-blockchain-hit-by-51-attack-leading-to-70k-double-spend)


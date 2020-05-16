# Plan


1. Geneza
   * [Hashcash](https://pl.wikipedia.org/wiki/Hashcash)
   * [podpis cyfrowy](https://pl.wikipedia.org/wiki/Podpis_cyfrowy)
   * Kryzys 2008/2009, ```./bitcoin-cli -rpcport=8332 -rpcpassword=*** getblock 000000000019d6689c085ae165831e934ff763ae46a2a6c172b3f1b60a8ce26f 2 | grep '"hex"' | awk -F: '{print $2}' | sed s/[^0-9a-z]//g | xxd -r -p | tr -c -d '[:print:]'``` (uruchomić Bitcoin: `bitcoind -chain=main -rpcport=8332 -rpcpassword=*** -server`)
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
   * [Lightning Network](https://lightning.network/lightning-network-paper.pdf) oraz [wytłumaczenie od Antonopolusa](https://www.youtube.com/watch?v=gF_ZQ_eijPs)
1. Historia
   * Hal Finney [Running Bitcoin](https://twitter.com/halfin/status/1110302988)
   * [HODL](https://bitcointalk.org/index.php?topic=375643.0)
   * [Pizza](https://bitcointalk.org/?topic=137.0)
   * Giełdy
   * Silkroad + Ross Ulbricht
   * Altcoiny - Litecoin, Dogecoin, Namecoin, Monero, Ethereum, Tether, ...
   * ICO
   * Scaling Debate - SegWit/sidechain/multisig/timelock/...
       * SegWit2X, UASF, Bitcoin Cash, BitPay, Coinbase, bitcoin.com, flippening
       * Lightning Network, Liquid, RSK, ...
       * [Artykuł na forbes](https://www.forbes.com/sites/laurashin/2017/11/12/bitcoin-cash-skyrockets-bitcoin-price-drops-as-civil-war-continues/#6525d33e35b5) [Jak wyglądało na polskim forum w czasie niedoszłego flippeningu](https://forum.bitcoin.pl/viewtopic.php?t=24513) oraz [komentarz N.Dorniera do BitPay i ich dość mętnych zagrań](https://twitter.com/NicolasDorier/status/898378514256207872)
       * [hashrate historia](https://bitinfocharts.com/comparison/hashrate-btc-bch-bsv.html#log)
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
   * Stock to flow
1. Do poczytania
   * Mastering Bitcoin - A. Antonopolus
   * The Bitcoin Standard (to ja mam na liście do przeczytania) - 
   * Programming Bitcoin - Jimmy Song
   * [lista u J.Loppa](https://www.lopp.net/bitcoin-information/books.html)
1. Do obejżenia
   * Meltem Demirors [Wystąpienie w kongresie USA](https://www.youtube.com/watch?v=uxhS8Bdddak) oraz na konferencji [Magical Crypto Friends](https://www.youtube.com/watch?v=UgKywMSDi20)
   * Andreas Antonopolus [Wystąpienie w kongresie Kanady](https://www.youtube.com/watch?v=xUNGFZDO8mM)
 

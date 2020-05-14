# Plan


1. Geneza
   * [Hashcash](https://pl.wikipedia.org/wiki/Hashcash)
   * [podpis cyfrowy](https://pl.wikipedia.org/wiki/Podpis_cyfrowy)
   * Kryzys 2008/2009, ```./bitcoin-cli -rpcconnect=192.168.0.16 getblock 000000000019d6689c085ae165831e934ff763ae46a2a6c172b3f1b60a8ce26f 2 | grep '"hex"' | awk -F: '{print $2}' | sed s/[^0-9a-z]//g | xxd -r -p```
   * [Liberty Reserve](https://en.wikipedia.org/wiki/Liberty_Reserve)
   * [drzewo Merkle](https://en.wikipedia.org/wiki/Merkle_tree) 
1. Składniki (publikacja Satoshiego)
   * łańcuch podpisów cyfrowych
   * łańcuch połączonych bloków
   * PoW
   * nagroda za blok
1. Ciekawsze kwestie techniczne
   * język script
   * OP_RETURN
1. Historia
   * Hal Finney
   * Pizza
   * Giełdy
   * Silkroad + Hans Ulbricht
   * Altcoiny - Litecoin, Dogecoin, Namecoin, Ethereum, Tether, ...
   * Scaling Debate - SegWit/sidechain/multisig/timelock/...
       * SegWit2X, UASF, Bitcoin Cash
       * Lightning Network, Liquid, 
1. Przemyślenia: technologia+ekonomia+społeczeństwo 

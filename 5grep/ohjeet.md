Löydä tekstipätkiä tiedostoista

1. Löydä tiedostosta `paljon_tekstia.txt` rivi, jossa esiintyy teksti `mjäyy`.
2. Löydä hakemistohelvetistä tiedosto, jossa esiintyy tekstipätkä `mjäyy`

Muista:
* `grep` komento etsii kaikki rivit jotka vastaavat annettua muotoa (regexia) (kts. regular expression).
* `grep hui kissa.txt` ettii kaikki rivit tiedostossa kissa.txt, jossa esiintyy tekstipätkä `hui` ja printtaa ne
* `grep -r hui elaintarinat/` etsii kaikista hakemiston `elaintarinat/` tiedostoista rivejä, joissa esiintyy tekstipätkä `hui`. 
* `jokukomento | grep hei` etsii komennon `jokukomento` ulostulosta kaikki rivit, jossa esiintyy `hei`. 
* Voit antaa grepille myös regexia. Saatat tarvita lisätä -E flagin ennen regexia.

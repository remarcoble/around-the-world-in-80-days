# Il giro del mondo in 80 giorni

Partendo dai dati contenuti nel file `./data/worldcities_ascii.csv` trovare per ogni città le 3 città più vicine ad essa.

Calcolare il tempo che ci vuole a spostarsi da una città a un suo vicino secondo queste regole:

- 2 ore per la città più vicina
- 4 ore per la seconda città più vicina
- 8 ore per la terza città più vicina

Inoltre il viaggio richiede:

- 2 ore aggiuntive se la città di destinazione è in un'altra nazione rispetto alla città di partenza
- 2 ore aggiuntive se la città di destinazione ha più di 200.000 abitanti
## Quesiti
1. Partendo da Londra e viaggiando sempre verso Est, è possible compiere il giro del mondo tornando a Londra in 80 giorni? Quanto tempo si impiega al minimo?

2. In caso non si possa compiere il giro del mondo partendo da Londra, da quali altre città è possibile compiere il giro del mondo?

3. Supponendo che da ogni città si possa viaggiare solo verso le 3 città a Est più vicine come cambia l'esito delle domande precedenti?

---

### Packages utilizzati:

- *numpy*
- *pandas*
- *dijkstra*
- *sklearn*
- *math*
- *csv*
- *ipyleaflet*
- *ipywidgets*

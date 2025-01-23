# ATP Kolokvij

## Dalí je u povijesti zapamćen po svojim snažnim i bizarnim slikama te kao jedan od najpoznatijih predstavnika nadrealizma u slikarstvu, a mnogi stručnjaci smatraju da su na njegov stil utjecali renesansni majstori.

![Slika 1](slika.jpg)

```
export class UserBookmark extends DurableObject {

  constructor( ctx, env ) {
    
    super(ctx, env);
    
    this.storage = ctx.storage;
    this.localSql = ctx.storage.sql;

    this.localSql.exec(`CREATE TABLE IF NOT EXISTS bookmark(
```

### Popis resursa
- [Tekst](https://hr.wikipedia.org/wiki/Glavna_stranica)
- [Slika](https://www.pexels.com/photo/misty-mountain-framed-by-evergreen-trees-30283157/)

### Numerirani popis
?

| | | |
| - | - | - |
|Naziv|verzija|autor|
|ATP kolokvij|1.0|Dominik Juricic|

- [x] Kreirati GitHub repozitorij nazvan atp-kolokvij
- [x] Dodati naslov projekta (H1)
- [x] Dodati kratki opis projekta (H2) – preuzeti tekst s Wikipedije
- [x] Dodati sliku – preuzeti s Unsplash ili Pexels
- [x] Dodati primjer koda – preuzeti s Gists
- [x] Dodati link na izvor slike i teksta
- [ ] Linkati README.md i LICENSE.md (obostrano)
- [ ] Napraviti popis (numerički i ne-numerički)
- [x] Izraditi kratku tablicu s informacijama o projektu
- [x] Napraviti commit promjena s odgovarajućom porukom
- [ ] Otvoriti pull request unutar vlastitog repozitorija
- [x] Dodati LICENSE.md datoteku s MIT licencom
- [x] Aktivirati GitHub Pages za repozitorij

[Licenca](LICENCE.md)

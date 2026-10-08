# Oppimispäiväkirja: Hajautettu git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet, jotka vaikuttivat tehtävän suorittamiseen?__

Paikallis ja etärepositorioiden käyttö oli tässä vaiheessa ainakin yksinkertaista. Haarojen käyttöä pitää vielä opiskella ja ymmärtää että milloin niitä käytetään ja miten.

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| git remote -v | näyttää repostorioon määritetyt etärepostorioluettelot ja niiden osoitteet |
| git remote add origin <osoit> | lisää github repostorion paikallisen repostorion etärepostorioksi nimellä origin |
| git push -u origin master | vie paikallisen master haaran githubiin ja asettaa sen seuraamaan origin/master haaraa |
| git switch -c new-feat | luo uuden haaran nimeltä new-feat ja siirtyy siihen |
| git fetch | hakee etärepostorion uusimmat muutokset, mutta ei yhdistä niitä nykyiseen haaraan |
| git merge origin/new-feat | yhdistää etärepostorion new-feat haaran muutokset paikalliseen new-feat haaraan |
# Oppimispäiväkirja: Paikallinen git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet?__

Tiedostojen luonti ja muokkaus oli helppoa. Peruuttamisetkin onnistuivat melko helposti.
Haarojen käytön periatteet olivat aluksi hieman epäselviä mutta pienen lukemisen jälkeen nekin selkenivät 

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| git init | Luodaan hakemistoon uusi git repositorio |
| git status | Näyttää repositorion nykyisen tilanteen ja muuttuneet tiedostot |
| git add <tiedosto> | Lisää kyseisen tiedoston seuraavaan talletukseen |
| git add . | Lisää kaikki muutokset seuraavaan talletukseen |
| git commit -m "viesti" | Tallentaa lisätyt muutokset git historiaan, "viesti" kommentin kanssa |
| git mv <vanha> <uusi> | Nimeää uudelleen tai siirtää tiedoston |
| git rm <tiedosto> | Poistaa gitin seuraaman tiedoston ja lisää poiston seuraavaan talletukseen |
| git log | Näyttää tehtyjen talletusten historian |
| git tag harjoitus2 | Lisää tunnisteen nykyiseen talletukseen |
| git restore <tiedosto> | Peruuttaa yksittäisen valitun tiedoston muutokset seuraavasta talletuksesta
| git restore . | Poistaa kaikkien seurattujen tiedostojen tallennettamattomat muutokset |
| git revert head | Luo uuden talletuksen, joka kumoaa viimeisimmön talletuksen muutokset |
| git branch | Näyttää paikalliset haarat ja aktiivisen haaran |
| git branch | Näyttää paikalliset sekä etärepositorion haarat |
| git switch -c <haara> | Luo uuden haaran ja vaihtaa siihen |
| git merge --no-ff tyylit | Yhdistää tyylit haaran aktiiviseen haaraan (master) ja tekee merge talletuksen |

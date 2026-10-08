# Oppimispäiväkirja: Hajautettu git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet, jotka vaikuttivat tehtävän suorittamiseen?__

Harjoitus 5 on ollut tähän asti haastavin. Muistin ohjelmistoprojekti-kurssilta, että gitin eri haarojen kanssa voi helposti tulla merge ja muita ongelmia. Myös kokonaisuutta on hieman vaikea hahmottaa, kun mukana on sekä paikallinen repositorio että etärepositorio ja monia eri haaroja.

Haarojen luominen ja niiden välillä siirtyminen oli kuitenkin helppoa. Tein tehtävänannon mukaisesti, komento kerrallaan, ja tarkistin tilanteen git status ja git branch komennoilla joka välissä.

## Osiossa käyttämäni Git-komennot

| git remote -v| näyttää paikalliseen repoon liitetyt etärepositoriot|
| git push -u origin main | vie paikallisen main-haaran GitHubiin ja yhdistää etähaaraan |
| git switch -c new-feat | luo uuden new-feat- haaran ja siirtyy samalla siihen|
| git branch | näyttää git haarat |
| git merge origin/new-feat | yhdistää new-feat- haaran muutokset paikalliseen haaraan |
| git switch main | vaihtaa main-haaraan |
| git merge new-feat |yhdistää new-feat- haaran muutokset main-haaraan|
| git status | näyttää repositorion ja haaran tilanteen |
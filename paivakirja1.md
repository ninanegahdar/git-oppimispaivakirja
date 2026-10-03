# Oppimispäiväkirja: Paikallinen git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet?__

2 Harjoituksessa harjoiteltiin perustoimintoja. Loin uuden Git-nimisen hakemiston ja samannimisen repositorion GitHubiin. Loin ja poistin tiedostoja ja tallensin muutoksen versionhallintaan. Tässä vaiheessa kaikki oli tuttua, eikä luonut ongelmia.

3 Harjoituksessa jouduin peruuttelemaan tehtyjä muutoksia. Kaikki onnistui aika suoraviivaisesti, sillä tein tehtävät askel askeleelta kurssimateriaalin esimerkkien mukaisesti. Vaikeinta on ehkä muistaa reset-, restore- ja revert-komentojen erot. Minulle uusi ja todella kätevä juttu oppia oli, että committien koko tunnistetta ei tarvitse kirjoittaa komennoissa, vaan seitsemän ensimmäistä merkkiä riittää.


## Osiossa käyttämäni Git-komennot

| git add | lisää tiedoston seuraavaan talletukseen |
| --------| ------ |
| git commit -m | tallettaa versionhallintaan |
| git push | vie ja tallentaa muutokset versionhallintaan|
| git rm | poistaa tiedoston |
| git mv | uudelleennimeää tiedoston |
| git status| näyttää työtilaan tehdyt muutokset|
| git log | näyttää commit-historian |
| git tag | lisää talletukseen tunnisteen |
| git reset | peruu 'git add' komennon |
| git restore | poistaa tehdyt muutokset ja palauttaa tiedostot aikaisempaan tilaan |
| git reset --hard | poistaa kaikki työtilaan tehdyt muutokset  |
| git revert| kumoaa aikaisemman commitin |
# Oppimispäiväkirja: Hajautettu git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet, jotka vaikuttivat tehtävän suorittamiseen?__

Hajautetun Gitin harjoituksissa vaikeinta oli aluksi ymmärtää paikallisen repositorion ja etärepositorion välinen ero. Myös push, pull ja fetch -komentojen tarkoitusten erottaminen vaati harjoittelua. Pull Requestien tekeminen GitHubissa oli aluksi hieman epäselvää, mutta käytännön tekeminen auttoi ymmärtämään, miten omassa haarassa tehdyt muutokset voidaan ehdottaa yhdistettäväksi toiseen haaraan.

Opin parhaiten tekemällä tehtävät vaihe vaiheelta ja kokeilemalla komentoja käytännössä. Virheilmoitukset auttoivat myös ymmärtämään, mitä Gitissä tapahtui. Esimerkiksi oppimispäiväkirjaa tehdessäni yritin aluksi puskea muutoksia opettajan repositorioon, mutta GitHub ilmoitti käyttöoikeusvirheestä. Tämän avulla opin, että Gitin origin voi osoittaa eri etärepositorioon ja että se voidaan vaihtaa omaan GitHub-repositorioon.

## Osiossa käyttämäni Git-komennot

git clone = Kopioi etärepositorion omalle tietokoneelle ja luo siitä paikallisen repositorion.
git remote -v = Näyttää, mihin etärepositorioon paikallinen repo on yhdistetty.
git remote set-url origin = Vaihtaa origin-etärepositorion osoitteen.
git push = Vie paikalliset commitit etärepositorioon.
git pull = Hakee etärepositorion muutokset ja yhdistää ne paikalliseen haaraan.
git fetch = Hakee tietoja etärepositoriosta muuttamatta vielä nykyistä haaraa.
git merge = Yhdistää yhden haaran muutokset toiseen haaraan.
git branch -a = Näyttää paikalliset ja etärepositorion haarat.
git push -u origin <haara> = Vie uuden haaran etärepositorioon ja yhdistää paikallisen haaran seurattavaan etähaaraan.
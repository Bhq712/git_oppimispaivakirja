# Oppimispäiväkirja: Paikallinen git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet?__

Aluksi Gitin käyttäminen tuntui hieman vaikealta, koska komentoja ja niiden tarkoituksia oli paljon. Erityisesti haarojen, commitien ja Gitin eri tilojen ymmärtäminen vaati harjoittelua. Myös komentorivin käyttäminen oli suhteellisen tuttua muilta kursseilta ja tämän tehtävän avulla sain paljon hyvää kertausta.

Helpointa oli tiedostojen lisääminen Gitin seurantaan, muutosten tallentaminen commitilla sekä Gitin tilan tarkistaminen. Opin parhaiten tekemällä tehtävät itse ja kokeilemalla komentoja käytännössä. Myös virheilmoituksista oli hyötyä, koska niiden avulla pystyin selvittämään, mitä olin tekemässä väärin. Jos jokin komento tai Gitin toiminta jäi epäselväksi, selvitin asian kokeilemalla ja palaamalla tehtävän ohjeisiin. Jos tämäkään ei auttanut, pyysin apua tekoälyltä, joka selitti missä vika oli.

## Osiossa käyttämäni Git-komennot

git init = Luo uuteen kansioon Git-repositorion.
git status = Näyttää repositorion nykyisen tilan ja esimerkiksi muuttuneet tai seuraamattomat tiedostot.
git add = Lisää tiedoston tai muutokset staging-alueelle seuraavaa committia varten.
git commit -m "viesti" = Tallentaa staging-alueella olevat muutokset Gitin historiaan annetulla viestillä.
git log	= Näyttää repositorion commit-historian.
git log --stat = Näyttää commit-historian sekä tiedostoihin tehdyt muutokset.
git branch = Näyttää paikalliset Git-haarat.
git switch = Vaihtaa Git-haarasta toiseen.
git tag = Luo tai näyttää Gitin tunnisteita eli tageja.
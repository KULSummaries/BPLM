# Samenvatting Beginselen van Productie en Logistiek Management

Samenvatting voor het vak "Beginselen van Productie en Logistiek Management" aan de KUL.

## De Samenvatting Verkrijgen
Je kan de samenvatting gemakkelijk [hier downloaden](https://www.sharelatex.com/github/repos/KULSummaries/BPLM). Er zal meteen gevraagd worden of je de logfile wilt downloaden, maar deze heb je niet nodig.

Om zelf de samenvatting te "bouwen" zul je de volgende dingen nodig hebben:
* [git](http://www.git-scm.com/)
* [texlive](https://www.tug.org/texlive/)
* ([make](https://www.gnu.org/software/make/))

Gebruikers van Linux en OSX kunnen dan gewoon naar hun terminal gaan en volgende commando's intypen:

``` bash
cd /your/preferred/directory
git clone https://github.com/KULSummaries/BPLM
cd BPLM/
```

Indien make op je systeem geïnstalleerd is, kan je gewoon volgend commando intypen:
```bash
make
```

Er zal nu een nieuwe map verschijnen genaamd "helpFiles". De samenvatting zelf verschijnen als "Summary.pdf" in de root folder van het project.

Indien je make niet hebt, kan je texlive rechtstreeks aanroepen. Volgend commando zal dan je samenvatting creëren:
``` bash
pdflatex -jobname Summary.pdf main.tex
```

Dit commando zal je tweemaal moeten uitvoeren om alle referenties binnen het document juist te krijgen.

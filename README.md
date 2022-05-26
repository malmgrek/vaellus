# Matkatavarat vaellukselle

Vaellusvarusteiden pakkaamisen avuksi muistilista, johon voi kätevästi merkitä
mitkä tavarat on jo pakattu: <https://malmgrek.github.io/vaellus> 

## HTML-tiedoston päivittäminen Emacsilla

Sivu on luotu Emacsin Org-mode paketin avulla ihmisen luettavan
`index.org`-tiedoston pohjalta. Ohje:

1. Määrittele muuttuja `(setq org-html-checkbox-type 'html)`.
2. Kutsu `org-export-to-html`.

Tällöin ruksituslaatikot tulostuu oikein.

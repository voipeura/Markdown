### Jotain ohjeita GitHubbiin

<h3>Git peruskomennot: git add, git commit, git status, git push, git branch</h3>

<h4>git add</h4>
Git add: komento lisää luodut tiedostot versiohallinnan piiriin
<h4>git commit</h4>
Git commit: komento lisää tiedoston uusimman tilan versiohallintaan
<h4>git status</h4>
Git status: komento tarkistaa, tiedostojen tilan, onko ne lisätty tai commitattu
<h4>git push</h4>
Git push: komento ikäänkuin työntää tiedot/tiedostot, tietovarastoon esim: GitHub
<h4>git branch</h4>
Git branch: luo haaran(git branch uusihaara) ja git branch tarkistaa, mikä haara on aktiivisena

<h3>Muita komentoja</h3>
<h4>Git checkout</h4>
Git checkout: komento vaihtaa käytössä olevan haaran(git checkout uusihaara)
<h4>Git revert</h4>
Git revert: komento poistaa committin
<h4>Git reset</h4>
Git reset: komento palaa tiettyyn vanhaan committiin. Komento poistaa kaikki tehdyt commitit viitatun commitin jälkeen. Komentoa ei voi käyttää julkisesti vaan on käytettävä git   revert komentoa
<h2>Paikallinen Git työhakemisto GitHubiin</h3>
<h4>Git init</h4>
Git init: komento ottaa versiohallinnan käyttöön työkansiossa. Sitten perus git add ja git commit komennot myös. Git remote add origin: komento kytkee työhakemiston GitHub   repositorioon.

GitHubiin pitää tehdä repository, johon se voidaan kytkeä ja lähettää tietoa

Forkkaamisen voi tehdä helpoiten GitHubissa. Se kopio tiedoston itselleen.

Vieraasta remotesta sisällön lataus git clone (osoite).

Komennolla git remote add upstream "verkkosivun linkki"

git remote -v tarkistaa

paikallisen työhakemiston tietojen puskeminen GitHubiin git push -u origin master

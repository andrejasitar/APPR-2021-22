# Analiza podatkov s programom R - 2021/22

Vzorčni repozitorij za projekt pri predmetu APPR v študijskem letu 2021/22. 

## Analiza vpisa v terciarno izobraževanje v Sloveniji in Evropi

V svoji projektni nalogi bom analizirala vpis v terciarno izobraževanje glede na način in vrsto izobraževanja ter spol v obdobju 2012 - 2019. Nato si bom podrobneje ogledala, kako se število vpisanih razlikuje glede na regije v Sloveniji za enako obdobje. Z ostalimi evropskimi državami bom primerjala le število vpisanihv terciarno izobraževanje glede na spol.

Tabela 1: Število vpisanihh v terciarno izobraževanje glede na vrsto izobraževanja
  - vrsta izobraževanja
  - način izobraževanja
  - spol
  - kohezijska regija
  - leto
  - število vpisanih
  
Tabela 2: Število vpisanihh v terciarno izobraževanje po statističnih regijah 
  - statistična regija
  - leto
  - število vpisanih

Tabela 3: Število vpisanihh v terciarno izobraževanje v evropskih državah
  - država
  - spol
  - leto
  - število vpisanih

Zanimalo me bo predvsem, koliko štedentov je vpisanih v terciarno izobraževanje v posameznih regijah, v kateri regiji jih je bilo največ v vsakem letu in kakšno je povprečje v obravnavanem obdobju. Pogledala si bom, kako se število vpisanih razlikuje glede na vrsto izobraževanja tj. visokošolsko univerzitetno, magistersko, doktorsko...


## Program

Glavni program in poročilo se nahajata v datoteki `projekt.Rmd`.
Ko ga prevedemo, se izvedejo programi, ki ustrezajo drugi, tretji in četrti fazi projekta:

* obdelava, uvoz in čiščenje podatkov: `uvoz/uvoz.r`
* analiza in vizualizacija podatkov: `vizualizacija/vizualizacija.r`
* napredna analiza podatkov: `analiza/analiza.r`

Vnaprej pripravljene funkcije se nahajajo v datotekah v mapi `lib/`.
Potrebne knjižnice so v datoteki `lib/libraries.r`
Podatkovni viri so v mapi `podatki/`.
Zemljevidi v obliki SHP, ki jih program pobere,
se shranijo v mapo `../zemljevidi/` (torej izven mape projekta).

---
title: Release 23.2.9
description: New release of Actual.
date: 2021-09-13T10:00
slug: release-23.2.9
authors: rich-howell
tags: [announcement, releases]
image: https://i.imgur.com/mErPwqL.png
hide_table_of_contents: false
---

## 23.2.9

**Docker tag: 23.2.9**

:::info

This release allows the user to bypass the SharedArrayBuffer warning that prevented the budget from loading in 23.2.5 when HTTPS was not in place with a certificate

:::

The release has the following improvement.

- Allow bypassing of SharedArrayBuffer warning when not using HTTPS

### Actual

Version: 23.2.9

#### Features

- [#644](https://github.com/actualbudget/actual/pull/644) Allow bypassing SharedArrayBuffer override — thanks [j-f1]

#### Bugfix

- [#640](https://github.com/actualbudget/actual/pull/640) Fix coloring of the “Split Transaction” button in the category picker — thanks [j-f1]
- [#641](https://github.com/actualbudget/actual/pull/641) Fix prop name for button to enable e2ee — thanks [j-f1]

#### Maintenance

- [#638](https://github.com/actualbudget/actual/pull/638) Allow the Netlify frontend to connect to arbitrary servers — thanks [j-f1]
- [#639](https://github.com/actualbudget/actual/pull/639) Move desktop-client deps to devDeps — thanks [j-f1]

### Actual Server

Version: 23.2.9

#### Maintenance

- [#128](https://github.com/actualbudget/actual-server/pull/128) Upgrade to ESM, update to latest dependencies — thanks [j-f1]
- [#131](https://github.com/actualbudget/actual-server/pull/131) Move source code to an src/ directory — thanks [j-f1]

[7brend7]: https://github.com/7brend7
[aaroneiche]: https://github.com/aaroneiche
[aharbis]: https://github.com/aharbis
[ajtrichards]: https://github.com/ajtrichards
[albertogasparin]: https://github.com/albertogasparin
[andremralves]: https://github.com/andremralves
[bdoherty]: https://github.com/bdoherty
[biohzrddd]: https://github.com/biohzrddd
[brtwrst]: https://github.com/brtwrst
[carkom]: https://github.com/carkom
[chylex]: https://github.com/chylex
[ciwchris]: https://github.com/ciwchris
[coliff]: https://github.com/coliff
[eberureon]: https://github.com/eberureon
[ejmurra]: https://github.com/ejmurra
[ezfe]: https://github.com/ezfe
[fry]: https://github.com/fry
[fstybel]: https://github.com/fstybel
[gsumpster]: https://github.com/gsumpster
[heilerich]: https://github.com/heilerich
[henrikmaa]: https://github.com/henrikmaa
[intiplink]: https://github.com/intiplink
[iurynogueira]: https://github.com/iurynogueira
[j-f1]: https://github.com/j-f1
[Jackenmen]: https://github.com/Jackenmen
[jamesmortensen]: https://github.com/jamesmortensen
[JazzaG]: https://github.com/JazzaG
[jlongster]: https://github.com/jlongster
[jlsjonas]: https://github.com/jlsjonas
[jonezy35]: https://github.com/jonezy35
[Kk-ships]: https://github.com/Kk-ships
[Kovah]: https://github.com/Kovah
[ldotlopez]: https://github.com/ldotlopez
[m3nu]: https://github.com/m3nu
[manuelcanepa]: https://github.com/manuelcanepa
[MatissJanis]: https://github.com/MatissJanis
[Miodec]: https://github.com/Miodec
[mnsrv]: https://github.com/mnsrv
[modrzew]: https://github.com/modrzew
[n1thun]: https://github.com/n1thun
[ostat]: https://github.com/ostat
[PartyLich]: https://github.com/PartyLich
[pmamberti]: https://github.com/pmamberti
[pole95]: https://github.com/pole95
[rianmcguire]: https://github.com/rianmcguire
[rich-howell]: https://github.com/rich-howell
[rickdoesdev]: https://github.com/rickdoesdev
[S3B4S]: https://github.com/S3B4S
[shall0pass]: https://github.com/shall0pass
[Shazib]: https://github.com/Shazib
[Silvenga]: https://github.com/Silvenga
[sinistersnare]: https://github.com/sinistersnare
[sudoCerb]: https://github.com/sudoCerb
[suryaatevellore]: https://github.com/suryaatevellore
[TheTrueCaligari]: https://github.com/TheTrueCaligari
[TomAFrench]: https://github.com/TomAFrench
[trevdor]: https://github.com/trevdor
[UnexomWid]: https://github.com/UnexomWid
[venkata-krishnas]: https://github.com/venkata-krishnas
[vincentscode]: https://github.com/vincentscode
[waseem-h]: https://github.com/waseem-h
[winklevos]: https://github.com/winklevos
[wmertens]: https://github.com/wmertens
[youngcw]: https://github.com/youngcw
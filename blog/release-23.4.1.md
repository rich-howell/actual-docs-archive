---
title: Release 23.4.1
description: New release of Actual.
date: 2021-09-13T10:00
slug: release-23.4.1
authors: rich-howell
tags: [announcement, releases]
image: https://i.imgur.com/mErPwqL.png
hide_table_of_contents: false
---

## 23.4.1

**Docker tag: 23.4.1**

The release fixes a issue with creating rules from the transaction list.

### Actual

Version: 23.4.1

#### Enhancements

- [#860](https://github.com/actualbudget/actual/pull/860) Allow goal template 'by' matches to compound — thanks [shall0pass]
- [#887](https://github.com/actualbudget/actual/pull/887) Mobile: unify "settings" page header with the style of "accounts" page — thanks [MatissJanis]
- [#891](https://github.com/actualbudget/actual/pull/891) Goal template can now use single decimal places to define targets — thanks [shall0pass]
- [#895](https://github.com/actualbudget/actual/pull/895) Improve error reporting for goal templates — thanks [shall0pass]
- [#900](https://github.com/actualbudget/actual/pull/900) Add "Daily" option to scheduled transactions — thanks [biohzrddd]

#### Bugfix

- [#865](https://github.com/actualbudget/actual/pull/865) Fix case-insensitive matching of strings for uppercase letters from non-English alphabets — thanks [Jackenmen]
- [#881](https://github.com/actualbudget/actual/pull/881) Autocomplete: do not show "create payee" option if the typed-in payee is an exact match of an existing payee — thanks [MatissJanis]
- [#882](https://github.com/actualbudget/actual/pull/882) Fix rule creation from account page (transaction list) — thanks [MatissJanis]
- [#883](https://github.com/actualbudget/actual/pull/883) Recognize numpad enter key as enter key — thanks [j-f1]
- [#886](https://github.com/actualbudget/actual/pull/886) Fill category field when selecting 'Create rule' from accounts screen — thanks [shall0pass]
- [#902](https://github.com/actualbudget/actual/pull/902) Remove currently viewed account from list of possible transfer accounts — thanks [biohzrddd]

#### Maintenance

- [#864](https://github.com/actualbudget/actual/pull/864) Don’t check for release notes on `release/*` branches — thanks [j-f1]
- [#869](https://github.com/actualbudget/actual/pull/869) Disable ESLint when building in CI (since we have a separate linting job) — thanks [j-f1]
- [#870](https://github.com/actualbudget/actual/pull/870) Remove duplicate migration and default-db.sqlite files — thanks [j-f1]
- [#877](https://github.com/actualbudget/actual/pull/877) Convert most CommonJS imports/exports to ESM — thanks [albertogasparin]
- [#884](https://github.com/actualbudget/actual/pull/884) Update `@typescript-eslint/*` packages to their latest versions — thanks [j-f1]
- [#889](https://github.com/actualbudget/actual/pull/889) Convert few other folders in `loot-core` to Typescript — thanks [albertogasparin]
- [#890](https://github.com/actualbudget/actual/pull/890) Add a CodeQL workflow to automatically scan for potential security issues — thanks [j-f1]
- [#893](https://github.com/actualbudget/actual/pull/893) Remove usage of `realpath` command in build script — thanks [j-f1]

### Actual Server

Version: 23.4.1

#### Features

- [#182](https://github.com/actualbudget/actual-server/pull/182) Add support for armv6l (Alpine-based images only) — thanks [intiplink]

#### Enhancements

- [#187](https://github.com/actualbudget/actual-server/pull/187) Add rate limiting to all server requests — thanks [j-f1]

#### Maintenance

- [#181](https://github.com/actualbudget/actual-server/pull/181) Don’t check for release notes on `release/*` branches — thanks [j-f1]
- [#185](https://github.com/actualbudget/actual-server/pull/185) Use the proper Typescript Babel preset — thanks [albertogasparin]

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
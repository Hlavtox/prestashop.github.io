---
layout: post
aliases: ["/news/coreweekly-week-01-2019"]
title:  "PrestaShop Core Weekly - Week 01 of 2019"
subtitle: "An inside look at the PrestaShop codebase"
date:   2019-01-11 17:30:00
authors: [ AntoineThomas ]
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase during the first week of the year, from Monday 31st of December 2018 to Sunday 06th of January 2019.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)


## General messages

Dear Developers,

First week of 2019 is a good start with 31 merged pull requests. But now that everybody is back, let's continue to contribute like the best weeks of 2018, and aim at minimum 40 pull request merged per week. That would be great! And remember, a small pull request, solving one problem, is easier to review and to merge than a very big one with changes in a lot of files and/or about many issues.

Since the beginning of the year, I have improved the first section of the core-weekly, with new figures about the PrestaShop project repositories on GitHub. In a few week, with a bit of history to show, I will try to share a chart so we can look at the trends.


## A quick update about PrestaShop's GitHub issues and pull requests:

- [36 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2018-12-31..2019-01-06) have been created in the project repositories
- [43 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2018-12-31..2019-01-06), including [11 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2018-12-31..2019-01-06)
- [66 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2018-12-31..2019-01-06) in the project repositories
- [40 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2018-12-31..2019-01-06), including [31 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2018-12-31..2019-01-06)

## Code changes in the 'develop' branch (for v1.7.6.0)

### Core

* [#11985](https://github.com/PrestaShop/PrestaShop/pull/11985): PHP unit test case static method calls. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#12010](https://github.com/PrestaShop/PrestaShop/pull/12010): Make filtering of LazyArrays return a new instance, by [@eternoendless](https://github.com/eternoendless)
* [#12015](https://github.com/PrestaShop/PrestaShop/pull/12015): fix typo in example nginx config file. Thank you [@mwht](https://github.com/mwht)


### Back office

* [#10774](https://github.com/PrestaShop/PrestaShop/pull/10774): Migration of "International > Localization > Currencies" page listing. Thank you [@tomas862](https://github.com/tomas862)
* [#11481](https://github.com/PrestaShop/PrestaShop/pull/11481): Add cover & menu thumbnail images deleting for category. Thank you [@sarjon](https://github.com/sarjon)
* [#11723](https://github.com/PrestaShop/PrestaShop/pull/11723): Migrate customer Add/Edit actions. Thank you [@sarjon](https://github.com/sarjon)
* [#11922](https://github.com/PrestaShop/PrestaShop/pull/11922): Fix searching issue in the Credit Slips page, by [@khouloudbelguith](https://github.com/khouloudbelguith)
* [#11932](https://github.com/PrestaShop/PrestaShop/pull/11932): Can't sort tax included for now, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#11936](https://github.com/PrestaShop/PrestaShop/pull/11936): Description has a max length and can not exceeded, by [@PierreRambaud](https://github.com/PierreRambaud)


### Front office

* [#10294](https://github.com/PrestaShop/PrestaShop/pull/10294): Fix minimum order amount for secondary currency. Thank you [@sadlyblue](https://github.com/sadlyblue)
* [#10297](https://github.com/PrestaShop/PrestaShop/pull/10297): Fix image dimensions in Product Card view. Thank you [@CaptainYouz](https://github.com/CaptainYouz)
* [#10487](https://github.com/PrestaShop/PrestaShop/pull/10487): Added breadcrumb to the manufacturers pages. Thank you [@SebBareyre](https://github.com/SebBareyre)
* [#11726](https://github.com/PrestaShop/PrestaShop/pull/11726): Force dni fields required if associated Country needs it, by [@jolelievre](https://github.com/jolelievre)
* [#11754](https://github.com/PrestaShop/PrestaShop/pull/11754): Fix wrong discount details on order page / on invoice, by [@tomlev](https://github.com/tomlev)


### Tests

* [#10477](https://github.com/PrestaShop/PrestaShop/pull/10477): Added an Error Data Listener, by [@mickaelandrieu](https://github.com/mickaelandrieu)
* [#11898](https://github.com/PrestaShop/PrestaShop/pull/11898): Fix travis script for running tests and fix broken tests, by [@matks](https://github.com/matks)
* [#12001](https://github.com/PrestaShop/PrestaShop/pull/12001): Filters in catalog page. Thank you [@ansar21mallouli](https://github.com/ansar21mallouli)
* [#12007](https://github.com/PrestaShop/PrestaShop/pull/12007): Delivery slip test. Thank you [@YosraAk](https://github.com/YosraAk)
* [#12013](https://github.com/PrestaShop/PrestaShop/pull/12013): Isolate legacy tests into suites to fix develop branch, by [@matks](https://github.com/matks)


## Code changes in the '1.7.5.x' branch (for v1.7.5.1)

### Install

* [#11937](https://github.com/PrestaShop/PrestaShop/pull/11937): Check if intl is installed in installer, by [@PierreRambaud](https://github.com/PierreRambaud)


## Code changes in modules, themes & tools


### Docker

* [#150](https://github.com/PrestaShop/docker/pull/150): Add libzip package to the base image, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#151](https://github.com/PrestaShop/docker/pull/151): Allow all languages to be installed with PrestaShop , by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Circuit Breaker

* [#2](https://github.com/PrestaShop/circuit-breaker/pull/2): Added exemple of use, by [@mickaelandrieu](https://github.com/mickaelandrieu)
* [#3](https://github.com/PrestaShop/circuit-breaker/pull/3): Introduced CB factory, by [@mickaelandrieu](https://github.com/mickaelandrieu)
* [#4](https://github.com/PrestaShop/circuit-breaker/pull/4): Make the creation of places more robust, by [@mickaelandrieu](https://github.com/mickaelandrieu)
* [#5](https://github.com/PrestaShop/circuit-breaker/pull/5): Introduced transaction and storage, by [@mickaelandrieu](https://github.com/mickaelandrieu)
* [#7](https://github.com/PrestaShop/circuit-breaker/pull/7): Fixed typo, by [@mickaelandrieu](https://github.com/mickaelandrieu)
* [#8](https://github.com/PrestaShop/circuit-breaker/pull/8): Implement Transaction + Storage, by [@mickaelandrieu](https://github.com/mickaelandrieu)
* [#10](https://github.com/PrestaShop/circuit-breaker/pull/10): Added unit tests for Storage, Transaction and Assert classes, by [@mickaelandrieu](https://github.com/mickaelandrieu)


### European VAT number

* [#7](https://github.com/PrestaShop/vatnumber/pull/7): Referencing issue #9928 of PrestaShop/PrestaShop. Thank you [@borlum](https://github.com/borlum)


## Changes in Documentation

* [#180](https://github.com/PrestaShop/docs/pull/180): Update _index.md "2007-2019 PrestaShop SA and Contributors", by [@ttoine](https://github.com/ttoine)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: @ansar21mallouli, @borlum, @CaptainYouz, @MathiasReker, @mwht, @sarjon, @sadlyblue, @SebBareyre, @tomas862, @YosraAk!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

---
layout: post
aliases: ["/news/coreweekly-week-29-2019"]
slug: "coreweekly-week-29-2019"
title:  "PrestaShop Core Weekly - Week 29 of 2019"
subtitle: "An inside look at the PrestaShop codebase"
date:   2019-07-31 12:30:00
authors: [ AntoineThomas ]
image: /assets/images/2017/04/core_weekly_banner.jpg
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 15th to Sunday 21th of July 2019.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)


## General messages

Dear Developers,

If you want to follow the work done on the upcoming patch release, please go on GitHub and watch the dedicated [milestone for PrestaShop 1.7.6.1](https://github.com/PrestaShop/PrestaShop/issues?q=is%3Aopen+is%3Aissue+milestone%3A1.7.6.1). You will see that some work has already been done (closed items). And of course, the work in progress is available too (opened items).


## A quick update about PrestaShop's GitHub issues and pull requests:

- [123 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2019-07-15..2019-07-21) have been created in the project repositories;
- [67 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2019-07-15..2019-07-21), including [13 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2019-07-15..2019-07-21) on the core;
- [49 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2019-07-15..2019-07-21) in the project repositories;
- [44 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2019-07-15..2019-07-21), including [32 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2019-07-15..2019-07-21).


## Code changes in the 'develop' branch

### Core

* [#14089](https://github.com/PrestaShop/PrestaShop/pull/14089): Fix #14085 Shop url with port in header HOST. Thank you [@202-ecommerce](https://github.com/202-ecommerce)
* [#14352](https://github.com/PrestaShop/PrestaShop/pull/14352): Move Cart secure_key setter at the right place, by [@jocel1](https://github.com/jocel1)
* [#14691](https://github.com/PrestaShop/PrestaShop/pull/14691): Update version to 1.7.7.0, by [@jolelievre](https://github.com/jolelievre)


### Back office

* [#14307](https://github.com/PrestaShop/PrestaShop/pull/14307): Fix manufacturers grid logo to not depend from shop context. Thank you [@zuk3975](https://github.com/zuk3975)
* [#14466](https://github.com/PrestaShop/PrestaShop/pull/14466): Fix saving of selected BO language. Thank you [@rokaszygmantas](https://github.com/rokaszygmantas)
* [#14540](https://github.com/PrestaShop/PrestaShop/pull/14540): Update Import controller to get errors for bad category import. Thank you [@webmak](https://github.com/webmak)
* [#14543](https://github.com/PrestaShop/PrestaShop/pull/14543): Wrong path of products thumbnails in back office, by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#14605](https://github.com/PrestaShop/PrestaShop/pull/14605): Do not use encodeURIComponent with POST data, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#14613](https://github.com/PrestaShop/PrestaShop/pull/14613): Broken translation in module list page:, by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#14656](https://github.com/PrestaShop/PrestaShop/pull/14656): Fix editing shop association in Category and Manufacturer. Thank you [@zuk3975](https://github.com/zuk3975)


### Front office

* [#12880](https://github.com/PrestaShop/PrestaShop/pull/12880): Add breadcrumb to the new products page. Thank you [@SebBareyre](https://github.com/SebBareyre)
* [#12881](https://github.com/PrestaShop/PrestaShop/pull/12881): Add breadcrumb to the prices drop page. Thank you [@SebBareyre](https://github.com/SebBareyre)
* [#12882](https://github.com/PrestaShop/PrestaShop/pull/12882): Add breadcrumb to the best sales page. Thank you [@SebBareyre](https://github.com/SebBareyre)
* [#12883](https://github.com/PrestaShop/PrestaShop/pull/12883):  Add breadcrumb to the suppliers page. Thank you [@SebBareyre](https://github.com/SebBareyre)
* [#13677](https://github.com/PrestaShop/PrestaShop/pull/13677): Submenu hides menu. Thank you [@YeLnatSs](https://github.com/YeLnatSs)
* [#14214](https://github.com/PrestaShop/PrestaShop/pull/14214): Handle shoppingcart error returns properly - part 2, by [@matks](https://github.com/matks)
* [#14558](https://github.com/PrestaShop/PrestaShop/pull/14558): Implement Schema ItemList for products listing & Fix Schema Product, by [@Progi1984](https://github.com/Progi1984)
* [#14587](https://github.com/PrestaShop/PrestaShop/pull/14587): Fix issue when searching for long words in FO, by [@matthieu-rolland](https://github.com/matthieu-rolland)


### Tests

* [#14231](https://github.com/PrestaShop/PrestaShop/pull/14231): PHPUnit no expectation annotation. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#14287](https://github.com/PrestaShop/PrestaShop/pull/14287): Behat tests for Category. Thank you [@sarjon](https://github.com/sarjon)
* [#14593](https://github.com/PrestaShop/PrestaShop/pull/14593): First POM implementation, by [@SimonGrn](https://github.com/SimonGrn)
* [#14612](https://github.com/PrestaShop/PrestaShop/pull/14612): Update docker for puppeteer, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#14725](https://github.com/PrestaShop/PrestaShop/pull/14725): Move travis scope from 5.6 to 7.1, by [@matks](https://github.com/matks)


### Web services

* [#8769](https://github.com/PrestaShop/PrestaShop/pull/8769): WS: Auto generate link_rewrite and do not require it when creating ca…. Thank you [@marekhanus](https://github.com/marekhanus)


## Code changes in the "1.7.6.x" branch (for v1.7.6.1)


### Back office

* [#14673](https://github.com/PrestaShop/PrestaShop/pull/14673): Fix Orders view page link to transform guest to customer, by [@matks](https://github.com/matks)
* [#14701](https://github.com/PrestaShop/PrestaShop/pull/14701): Fix log delete all action on Logs page, by [@matks](https://github.com/matks)


## Code changes in modules, themes & tools

### Shopping cart

* [#41](https://github.com/PrestaShop/ps_shoppingcart/pull/41): The modal "add to cart confirmation" is not displayed on error. Thank you [@jf-viguier](https://github.com/jf-viguier)


### Decimal

* [#5](https://github.com/PrestaShop/decimal/pull/5): Add support for exponential notation, by [@eternoendless](https://github.com/eternoendless)


### TranslationFiles

* [#6](https://github.com/PrestaShop/TranslationFiles/pull/6): Add translations files for 1.7.7, update latest on 1.7.6, by [@jolelievre](https://github.com/jolelievre)


### Customer reassurance block

* [#20](https://github.com/PrestaShop/blockreassurance/pull/20): Major refactoring, by [@Progi1984](https://github.com/Progi1984)
* [#21](https://github.com/PrestaShop/blockreassurance/pull/21): Some fixes for v4, by [@matks](https://github.com/matks)


### classic-rocket

* [#74](https://github.com/PrestaShop/classic-rocket/pull/74): Remove bs class and add utilities + make the button more ergonomic on phone. Thank you [@Kmoulun](https://github.com/Kmoulun)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: @202-ecommerce, @jf-viguier, @Kmoulun, @marekhanus, @MathiasReker, @rokaszygmantas, @sarjon, @SebBareyre, @webmak, @YeLnatSs, @zuk3975!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

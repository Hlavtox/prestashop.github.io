---
layout: post
aliases: ["/news/coreweekly-week-37-2019"]
title:  "PrestaShop Core Weekly - Week 37 of 2019"
subtitle: "An inside look at the PrestaShop codebase"
date:   2019-10-08 10:30:00
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
icon: icon-calendar
tags:
 - core-monthly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 9th of September to Sunday 15th of September 2019.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)


## A quick update about PrestaShop's GitHub issues and pull requests:

- [72 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2019-09-09..2019-09-15) have been created in the project repositories;
- [64 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2019-09-09..2019-09-15), including [8 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2019-09-09..2019-09-15) on the core;
- [56 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2019-09-09..2019-09-15) in the project repositories;
- [115 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2019-09-09..2019-09-15), including [43 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2019-09-09..2019-09-15).


## Code changes in the 'develop' branch

### Core

* [#15518](https://github.com/PrestaShop/PrestaShop/pull/15518): Update README, by [@matks](https://github.com/matks)

* [#15447](https://github.com/PrestaShop/PrestaShop/pull/15447): Re-enable port in shop domains, by [@matks](https://github.com/matks)

* [#15340](https://github.com/PrestaShop/PrestaShop/pull/15340): Update minimum compatibility to PHP 7.1.3, by [@eternoendless](https://github.com/eternoendless)

### Back office

* [#15429](https://github.com/PrestaShop/PrestaShop/pull/15429): Fix Add an Employee Handler with int casting required, by [@matks](https://github.com/matks)

* [#14925](https://github.com/PrestaShop/PrestaShop/pull/14925): Copy images from SCSS directory to public for the new-theme (to improve the release ZIP), by [@Progi1984](https://github.com/Progi1984)

### Tests

* [#15519](https://github.com/PrestaShop/PrestaShop/pull/15519): Fix Close browser after each scenario, by [@boubkerbribri](https://github.com/boubkerbribri)

* [#15509](https://github.com/PrestaShop/PrestaShop/pull/15509): Remove the smoke tests campaign - Puppeteer . Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)

* [#15470](https://github.com/PrestaShop/PrestaShop/pull/15470): Add Checkout FO to Sanity tests puppeteer, by [@boubkerbribri](https://github.com/boubkerbribri)

* [#15421](https://github.com/PrestaShop/PrestaShop/pull/15421): Cart FO tests with puppeteer - Sanity tests campaign. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)

## Code changes in modules, themes & tools

### Faceted search module

* [#141](https://github.com/PrestaShop/ps_facetedsearch/pull/141): Repair dev branch, by [@PierreRambaud](https://github.com/PierreRambaud)

* [#138](https://github.com/PrestaShop/ps_facetedsearch/pull/138): Calculate the number of available products with the stock management, by [@PierreRambaud](https://github.com/PierreRambaud)

* [#137](https://github.com/PrestaShop/ps_facetedsearch/pull/137): Revert "Calculate the number of available products with the stock management", by [@PierreRambaud](https://github.com/PierreRambaud)

* [#136](https://github.com/PrestaShop/ps_facetedsearch/pull/136): Fix wrong filter price, need match shop current. Thank you [@alex4102](https://github.com/alex4102)

* [#135](https://github.com/PrestaShop/ps_facetedsearch/pull/135): Use fetch method instead of render to allow override, by [@PierreRambaud](https://github.com/PierreRambaud)

* [#132](https://github.com/PrestaShop/ps_facetedsearch/pull/132): Calculate the number of available products with the stock management, by [@PierreRambaud](https://github.com/PierreRambaud)

* [#130](https://github.com/PrestaShop/ps_facetedsearch/pull/130): Add hook for Specifc Prices and move price min and max from rounded integer to decimal, by [@PierreRambaud](https://github.com/PierreRambaud)

* [#129](https://github.com/PrestaShop/ps_facetedsearch/pull/129): Use p tag instead h1 for filters, by [@PierreRambaud](https://github.com/PierreRambaud)

### Changes in developer documentation

* [#344](https://github.com/PrestaShop/docs/pull/344): Fix bad links and empty index page, by [@eternoendless](https://github.com/eternoendless)

* [#343](https://github.com/PrestaShop/docs/pull/343): Provide more module examples to get started, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)

* [#340](https://github.com/PrestaShop/docs/pull/340): Fix a spelling mistake in the doc. Thank you [@senkuu](https://github.com/senkuu)

* [#334](https://github.com/PrestaShop/docs/pull/334): Explain how to use Symfony service overrides and decorations, by [@matks](https://github.com/matks)

* [#329](https://github.com/PrestaShop/docs/pull/329): Added a table that sum up supported Symfony features, by [@mickaelandrieu](https://github.com/mickaelandrieu)

* [#324](https://github.com/PrestaShop/docs/pull/324): Fix bad link on Grid Actions reference page, by [@matks](https://github.com/matks)

* [#321](https://github.com/PrestaShop/docs/pull/321): Improve documentation on module translation, by [@eternoendless](https://github.com/eternoendless)

* [#317](https://github.com/PrestaShop/docs/pull/317): Add precisions for custom hooks. Thank you [@jf-viguier](https://github.com/jf-viguier)

* [#315](https://github.com/PrestaShop/docs/pull/315): Add server parameter to registerjavascript. Thank you [@zalexki](https://github.com/zalexki)

* [#288](https://github.com/PrestaShop/docs/pull/288): Improve doc for module's services.yml file. Thank you [@aziule](https://github.com/aziule)

* [#270](https://github.com/PrestaShop/docs/pull/270): How to add grid actions tutorial, by [@mickaelandrieu](https://github.com/mickaelandrieu)

### Block reassurance module

* [#26](https://github.com/PrestaShop/blockreassurance/pull/26): Revert "Release 4.0.0", by [@matks](https://github.com/matks)

* [#25](https://github.com/PrestaShop/blockreassurance/pull/25): Updated Readme & License & Enabled Release Drafter, by [@Progi1984](https://github.com/Progi1984)

* [#24](https://github.com/PrestaShop/blockreassurance/pull/24): Release 4.0.0, by [@Progi1984](https://github.com/Progi1984)

* [#22](https://github.com/PrestaShop/blockreassurance/pull/22): Last module tech improvements for v4, by [@Progi1984](https://github.com/Progi1984)

### Classic-rocket theme

* [#94](https://github.com/PrestaShop/classic-rocket/pull/94): Add missing classes on product miniatures. Thank you [@micka-fdz](https://github.com/micka-fdz)

* [#93](https://github.com/PrestaShop/classic-rocket/pull/93): Remove duplicate on smarty block name. Thank you [@micka-fdz](https://github.com/micka-fdz)

* [#81](https://github.com/PrestaShop/classic-rocket/pull/81): Fix padding and margin spacer. Thank you [@Kmoulun](https://github.com/Kmoulun)

### PrestaShop Specifications

* [#69](https://github.com/PrestaShop/prestashop-specs/pull/69): Shipping > Carrier > add new/edit. Thank you [@samuel-pires](https://github.com/samuel-pires)

### PrestaShop Docker images

* [#178](https://github.com/PrestaShop/docker/pull/178): Update mysql-client dep to default-mysql-client, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)

* [#176](https://github.com/PrestaShop/docker/pull/176): Fix README screenshot image URL, by [@matks](https://github.com/matks)

* [#175](https://github.com/PrestaShop/docker/pull/175): Release 1761, by [@matks](https://github.com/matks)

### Prestonbot

* [#89](https://github.com/PrestaShop/prestonbot/pull/89): Switch dependencies to symfony/symfony instead of symfony/lts, by [@matks](https://github.com/matks)

* [#87](https://github.com/PrestaShop/prestonbot/pull/87): Add version number API route, by [@matks](https://github.com/matks)

### Wire payment module

* [#45](https://github.com/PrestaShop/ps_wirepayment/pull/45): Update module short description, by [@colinegin](https://github.com/colinegin)

<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: @PierreRambaud, @eternoendless, @Quetzacoalt91, @boubkerbribri, @alex4102, @matks, @nesrineabdmouleh, @micka-fdz, @Progi1984, @senkuu, @samuel-pires, @colinegin, @damiandominella, @mickaelandrieu, @Kmoulun, @jf-viguier, @zalexki, @aziule!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

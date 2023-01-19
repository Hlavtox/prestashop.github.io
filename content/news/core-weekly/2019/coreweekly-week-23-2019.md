---
layout: post
aliases: ["/news/coreweekly-week-23-2019"]
title:  "PrestaShop Core Weekly - Week 23 of 2019"
subtitle: "An inside look at the PrestaShop codebase"
date:   2019-06-10 16:30:00
authors: [ AntoineThomas ]
icon: icon-calendar
tags:
 - core-monthly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 3rd to Sunday 10th of June 2019.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)


## General messages

Dear Developers,

This is the very last week to finish the beta tests and fix all discovered bugs and regression. Then, time for the first release candidate will come. The target is still to be able to release 1.7.6.0 at the end of June.

You can track the work being done with the dedicated [1.7.6 Kanban on GitHub](https://github.com/PrestaShop/PrestaShop/projects/4). And if you want to help, just pick a task, write some code, and open a pull request.


## A quick update about PrestaShop's GitHub issues and pull requests:

- [72 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2019-06-03..2019-06-10) have been created in the project repositories;
- [59 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2019-06-03..2019-06-10), including [11 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2019-06-03..2019-06-10) on the core;
- [40 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2019-06-03..2019-06-10) in the project repositories;
- [48 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2019-06-03..2019-06-10), including [34 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2019-06-03..2019-06-10).


## Code changes in the 'develop' branch

### Core

* [#14051](https://github.com/PrestaShop/PrestaShop/pull/14051): Merge 1.7.6.x to develop - 01/06/2019, by [@matks](https://github.com/matks)

* [#14099](https://github.com/PrestaShop/PrestaShop/pull/14099): Merge 1.7.6.x to develop - 06/06/2019, by [@matks](https://github.com/matks)
* [#14130](https://github.com/PrestaShop/PrestaShop/pull/14130): Merge 1.7.6.x to develop - 10/06/2019 [travis investigation - dont merge/close], by [@matks](https://github.com/matks)
* [#14133](https://github.com/PrestaShop/PrestaShop/pull/14133): Merge 1.7.6.x to develop - 10/06/2019, by [@matks](https://github.com/matks)
* [#14134](https://github.com/PrestaShop/PrestaShop/pull/14134): Combine consecutive issets(), by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Back office

* [#13382](https://github.com/PrestaShop/PrestaShop/pull/13382): Change input type for specific price reduction. Thank you [@YeLnatSs](https://github.com/YeLnatSs)
* [#13515](https://github.com/PrestaShop/PrestaShop/pull/13515): Migrate Sell > Catalog Brands & Suppliers > Suppliers view action. Thank you [@zuk3975](https://github.com/zuk3975)
* [#13894](https://github.com/PrestaShop/PrestaShop/pull/13894): displayBackOfficeTop hook should be in nav container. Thank you [@jf-viguier](https://github.com/jf-viguier)
* [#13971](https://github.com/PrestaShop/PrestaShop/pull/13971): Update AdminStatsController.php. Thank you [@ComonSoft](https://github.com/ComonSoft)
* [#14004](https://github.com/PrestaShop/PrestaShop/pull/14004): Fix generate path thumbnail image. Thank you [@dariusakafest](https://github.com/dariusakafest)


### Front office

* [#13383](https://github.com/PrestaShop/PrestaShop/pull/13383): Some UI improvements for Front-office. Thank you [@YeLnatSs](https://github.com/YeLnatSs)
* [#14033](https://github.com/PrestaShop/PrestaShop/pull/14033): Introduce FO JS event showErrorNextToAddtoCartButton to handle shoppingcart error returns, by [@matks](https://github.com/matks)


### Tests

* [#13790](https://github.com/PrestaShop/PrestaShop/pull/13790): Add Behat tests for Currency Domain. Thank you [@sarjon](https://github.com/sarjon)


## Code changes in the "1.7.6.x" branch (for v1.7.6.0)

### Core

* [#14027](https://github.com/PrestaShop/PrestaShop/pull/14027): Fix BC break on Toggle column parameter. Thank you [@sarjon](https://github.com/sarjon)


### Back office

* [#13919](https://github.com/PrestaShop/PrestaShop/pull/13919): Tax must be returned depending on PS_TAX_DISPLAY only, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#13923](https://github.com/PrestaShop/PrestaShop/pull/13923): Make sure index exist before getting value for gift message, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#14008](https://github.com/PrestaShop/PrestaShop/pull/14008): adds missing form data arguments in hooks. Thank you [@tomas862](https://github.com/tomas862)
* [#14021](https://github.com/PrestaShop/PrestaShop/pull/14021): Improved error handling when theme is uploaded or activated. Thank you [@tomas862](https://github.com/tomas862)
* [#14028](https://github.com/PrestaShop/PrestaShop/pull/14028): Add explanations about SEO cards. Thank you [@sarjon](https://github.com/sarjon)
* [#14029](https://github.com/PrestaShop/PrestaShop/pull/14029): Missing legacy link for themes page. Thank you [@tomas862](https://github.com/tomas862)
* [#14084](https://github.com/PrestaShop/PrestaShop/pull/14084): Fixes updating name and symbol for currency. Thank you [@sarjon](https://github.com/sarjon)
* [#14091](https://github.com/PrestaShop/PrestaShop/pull/14091): Do not use specific prices when displaying price with tax in BO product catalog, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#14107](https://github.com/PrestaShop/PrestaShop/pull/14107): Do not allow the selection of any subcategories, by [@PierreRambaud](https://github.com/PierreRambaud)


### Front office

* [#14075](https://github.com/PrestaShop/PrestaShop/pull/14075): Fix: If Ask for birth date option is disabled, an exception is displayed in the FO. Thank you [@OneDotIT](https://github.com/OneDotIT)
* [#14079](https://github.com/PrestaShop/PrestaShop/pull/14079): Update Smarty comments to reflect related blocks. Thank you [@prestamodule](https://github.com/prestamodule)


### Tests

* [#14053](https://github.com/PrestaShop/PrestaShop/pull/14053):  Add 'disable dev shm usage' to chrome options for headless chrome, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#14055](https://github.com/PrestaShop/PrestaShop/pull/14055): Using shm_size in docker File instead of 'disable dev shm usage' in chromeOptions , by [@boubkerbribri](https://github.com/boubkerbribri)
* [#14060](https://github.com/PrestaShop/PrestaShop/pull/14060): Fix CLDR Unit tests, by [@eternoendless](https://github.com/eternoendless)


## Code changes in modules, themes & tools

### PrestaShop Coding Standards

* [#7](https://github.com/PrestaShop/php-coding-standards/pull/7): Add autoload when phpstan is hidden behind symlink, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Live demo devices




### Docker Internal images




### Faceted search

* [#76](https://github.com/PrestaShop/ps_facetedsearch/pull/76): Create a better indexation and add tests, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#81](https://github.com/PrestaShop/ps_facetedsearch/pull/81): Bump to 3.0.3, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#84](https://github.com/PrestaShop/ps_facetedsearch/pull/84): Restore what happened on master branch, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#85](https://github.com/PrestaShop/ps_facetedsearch/pull/85): Release version 3.0.3, by [@PierreRambaud](https://github.com/PierreRambaud)


## Changes in Documentation

* [#285](https://github.com/PrestaShop/docs/pull/285): Remove IIS from possible system environments, by [@matks](https://github.com/matks)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: @ComonSoft, @dariusakafest, @jf-viguier, @OneDotIT, @prestamodule, @sarjon, @tomas862, @YeLnatSs, @zuk3975!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

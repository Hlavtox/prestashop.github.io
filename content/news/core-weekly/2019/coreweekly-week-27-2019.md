---
layout: post
aliases: ["/news/coreweekly-week-27-2019"]
title:  "PrestaShop Core Weekly - Week 27 of 2019"
subtitle: "An inside look at the PrestaShop codebase"
date:   2019-07-29 11:00:00
authors: [ AntoineThomas ]
image: /assets/images/2017/04/core_weekly_banner.jpg
icon: icon-calendar
tags:
 - core-monthly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 1st to Sunday 07th of July 2019.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)


## General messages

Dear Developers,

Last week was a very warm week, right? Did you find a solution to stay productive in your area?

If week 26 was a small week considering the numbers of pull requests, week 27 is one of the biggest of this year ! Work on 1.7.7 has started on the develop branch, and the work to finish the 1.7.6 has been merged. Also, a lot of work has been done on modules. Well done!

If week 26 was a small week considering the numbers of pull requests, week 27 is one of the biggest of this year! Work on the develop branch is very active again to prepare the 1.7.7, and the work to finish the 1.7.6 has been merged. Also, a lot of work has been done on modules. Well done!


## A quick update about PrestaShop's GitHub issues and pull requests:

- [61 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2019-07-01..2019-07-07) have been created in the project repositories;
- [56 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2019-07-01..2019-07-07), including [12 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2019-07-01..2019-07-07) on the core;
- [59 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2019-07-01..2019-07-07) in the project repositories;
- [78 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2019-07-01..2019-07-07), including [56 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2019-07-01..2019-07-07).


## Code changes in the 'develop' branch

### Core

* [#14043](https://github.com/PrestaShop/PrestaShop/pull/14043): Check if Combination id is set before deleting Associations from data…. Thank you [@kazeno](https://github.com/kazeno)
* [#14403](https://github.com/PrestaShop/PrestaShop/pull/14403): Fix cookie collisions from PR # 14116 and improve overall security. Thank you [@mvorisek](https://github.com/mvorisek)
* [#14425](https://github.com/PrestaShop/PrestaShop/pull/14425): Merge 1.7.6.x to develop - 28/06/2019  , by [@matks](https://github.com/matks)
* [#14459](https://github.com/PrestaShop/PrestaShop/pull/14459): Merge 1.7.6.x to develop - 03/07/2019, by [@matks](https://github.com/matks)
* [#14510](https://github.com/PrestaShop/PrestaShop/pull/14510): Merge 1.7.6.x to develop - 05/07/2019, by [@matks](https://github.com/matks)


### Back office

* [#10780](https://github.com/PrestaShop/PrestaShop/pull/10780): Custom error pages. Thank you [@sarjon](https://github.com/sarjon)
* [#13959](https://github.com/PrestaShop/PrestaShop/pull/13959): BO : JS files duplicated. Thank you [@idnovate](https://github.com/idnovate)
* [#14223](https://github.com/PrestaShop/PrestaShop/pull/14223): Bugfix: Fix unescaped dash in character group in regex. Thank you [@mvorisek](https://github.com/mvorisek)
* [#14310](https://github.com/PrestaShop/PrestaShop/pull/14310): Adds missing fields validation in tax create/edit handlers. Thank you [@zuk3975](https://github.com/zuk3975)
* [#14450](https://github.com/PrestaShop/PrestaShop/pull/14450): Whitelist filters for the Logs Page. Thank you [@Progi1984](https://github.com/Progi1984)


### Front office

* [#14049](https://github.com/PrestaShop/PrestaShop/pull/14049): Allow template vars override in hook actionFrontControllerSetVariables, by [@Matt75](https://github.com/Matt75)
* [#14263](https://github.com/PrestaShop/PrestaShop/pull/14263): Fix display voucher conversion between currencies, by [@tomlev](https://github.com/tomlev)
* [#14422](https://github.com/PrestaShop/PrestaShop/pull/14422): Refactor theme usage of product flags - apply DRY, by [@matks](https://github.com/matks)
* [#14452](https://github.com/PrestaShop/PrestaShop/pull/14452): Permit to buy a product without stock when other combination have stock and unavailable product attributes are not displayed. Thank you [@Progi1984](https://github.com/Progi1984)


### Tests

* [#14491](https://github.com/PrestaShop/PrestaShop/pull/14491): Disable Selenium Guest scenario as it fails randomly, by [@matks](https://github.com/matks)


## Code changes in the "1.7.6.x" branch (for v1.7.6.0)

### Core

* [#14438](https://github.com/PrestaShop/PrestaShop/pull/14438): Testing the factory with number and price specifications, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#14453](https://github.com/PrestaShop/PrestaShop/pull/14453): Update facetedsearch to 3.0.6, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#14503](https://github.com/PrestaShop/PrestaShop/pull/14503): Update changelog for 1.7.6.0 RC 2, by [@matks](https://github.com/matks)


### Back office

* [#14460](https://github.com/PrestaShop/PrestaShop/pull/14460): Ignore index.php files in Doctrine entities scanning, by [@jolelievre](https://github.com/jolelievre)


### Front office

* [#14444](https://github.com/PrestaShop/PrestaShop/pull/14444): Check if selected address belongs to user, by [@PierreRambaud](https://github.com/PierreRambaud)


### Tests

* [#14467](https://github.com/PrestaShop/PrestaShop/pull/14467): Remove unwanted e2e tests, by [@PierreRambaud](https://github.com/PierreRambaud)



## Code changes in modules, themes & tools

### Google sitemap

* [#106](https://github.com/PrestaShop/gsitemap/pull/106): Do not call getIsset() with getValue(), by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#107](https://github.com/PrestaShop/gsitemap/pull/107): Add all images of a product to the sitemap, instead of only the cover image. Thank you [@Pixep](https://github.com/Pixep)


### Nightly-board

* [#9](https://github.com/PrestaShop/nightly-board/pull/9): Disable reports, by [@PierreRambaud](https://github.com/PierreRambaud)


### Gamification

* [#61](https://github.com/PrestaShop/gamification/pull/61): Fix the deprecated create_function for PHP 7.2, by [@eternoendless](https://github.com/eternoendless)
* [#67](https://github.com/PrestaShop/gamification/pull/67): Undefined variable when running in fancybox, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#68](https://github.com/PrestaShop/gamification/pull/68): Bump version to 2.3.1, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#69](https://github.com/PrestaShop/gamification/pull/69): Release 2.3.1, by [@PierreRambaud](https://github.com/PierreRambaud)


### Example Module Mailtheme

* [#1](https://github.com/PrestaShop/example_module_mailtheme/pull/1): Update modules after changes from the core, use two different templat…, by [@jolelievre](https://github.com/jolelievre)
* [#2](https://github.com/PrestaShop/example_module_mailtheme/pull/2): Update min version, by [@jolelievre](https://github.com/jolelievre)


### CsaGuzzleBundle

* [#2](https://github.com/PrestaShop/CsaGuzzleBundle/pull/2): Allow PHP 7.1+ support with Guzzle 5. Thank you [@Progi1984](https://github.com/Progi1984)


### Faceted search

* [#94](https://github.com/PrestaShop/ps_facetedsearch/pull/94): Uninstall module used on PS 1.6 before using this one, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#102](https://github.com/PrestaShop/ps_facetedsearch/pull/102): Make filter show limit working again, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#103](https://github.com/PrestaShop/ps_facetedsearch/pull/103): Fix facet display when there is only one filter, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#104](https://github.com/PrestaShop/ps_facetedsearch/pull/104): Split currency if a ; is present in the format string, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#105](https://github.com/PrestaShop/ps_facetedsearch/pull/105): Fix for cache problem when used as widget. Thank you [@iqit-commerce](https://github.com/iqit-commerce)
* [#106](https://github.com/PrestaShop/ps_facetedsearch/pull/106): Bump to 3.0.6, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#107](https://github.com/PrestaShop/ps_facetedsearch/pull/107): Release 3.0.6, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#109](https://github.com/PrestaShop/ps_facetedsearch/pull/109): Fix ps_facetedsearch.tpl vars. Thank you [@davidglezz](https://github.com/davidglezz)
* [#110](https://github.com/PrestaShop/ps_facetedsearch/pull/110): Do not use seoUrl if user do not want to use it, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#111](https://github.com/PrestaShop/ps_facetedsearch/pull/111): Fix ie11 compatibility, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#112](https://github.com/PrestaShop/ps_facetedsearch/pull/112): Bump to 3.1.0, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#113](https://github.com/PrestaShop/ps_facetedsearch/pull/113): Release 3.1.0, by [@PierreRambaud](https://github.com/PierreRambaud)


### Google Adwords

* [#6](https://github.com/PrestaShop/gadwords/pull/6): Deploy v2.0.0 of the gadwords module, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#7](https://github.com/PrestaShop/gadwords/pull/7): Fix typo error on module installation, by [@apacios](https://github.com/apacios)
* [#8](https://github.com/PrestaShop/gadwords/pull/8): Bump version to 2.0.1, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#9](https://github.com/PrestaShop/gadwords/pull/9): Deploy v2.0.1 of the gadwords module, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Auto Upgrade

* [#284](https://github.com/PrestaShop/autoupgrade/pull/284): Display a notice if PHP is below v7.1, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#325](https://github.com/PrestaShop/autoupgrade/pull/325): Prepend and optimize autoloader, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#326](https://github.com/PrestaShop/autoupgrade/pull/326): Add PHPDoc & log when module switch the current theme, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#327](https://github.com/PrestaShop/autoupgrade/pull/327): Update logs around zip upgrade, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#328](https://github.com/PrestaShop/autoupgrade/pull/328): Bump version to 4.9.0, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### classic-rocket

* [#51](https://github.com/PrestaShop/classic-rocket/pull/51): Error alert is not shown on update cart error. Thank you [@morfin](https://github.com/morfin)


## Changes in documentation

* [#269](https://github.com/PrestaShop/docs/pull/269): Email theme generation documentation, by [@jolelievre](https://github.com/jolelievre)
* [#299](https://github.com/PrestaShop/docs/pull/299): Typo. Thank you [@idnovate](https://github.com/idnovate)
* [#300](https://github.com/PrestaShop/docs/pull/300): Doctrine usage, services definition, modern tabs, by [@jolelievre](https://github.com/jolelievre)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: @davidglezz, @idnovate, @iqit-commerce, @kazeno, @morfin, @mvorisek, @Pixep, @Progi1984, @zuk3975!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

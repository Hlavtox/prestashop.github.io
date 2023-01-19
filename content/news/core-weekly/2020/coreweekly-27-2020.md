---
layout: post
aliases: ["/news/coreweekly-27-2020"]
title:  "PrestaShop Core Weekly - Week 27 of 2020"
subtitle: "An inside look at the PrestaShop codebase"
date:   2020-07-08
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
twitter_image: /assets/images/theme/banner-core-weekly.jpg
icon: icon-calendar
tags:
 - core-monthly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 29th of June to Sunday 5th of July 2020.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)

## General messages

PrestaShop [1.7.6.6](https://build.prestashop.com/news/prestashop-1-7-6-6-maintenance-release/) and [1.7.6.7](https://build.prestashop.com/news/prestashop-1-7-6-7-maintenance-release/) have been released, don't forget to update as they fix security issues and regressions.


## A quick update about PrestaShop's GitHub issues and pull requests:

- [68 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2020-06-29..2020-07-05) have been created in the project repositories;
- [52 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2020-06-29..2020-07-05), including [15 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2020-06-29..2020-07-05) on the core;
- [41 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2020-06-29..2020-07-05) in the project repositories;
- [28 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2020-06-29..2020-07-05), including [23 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2020-06-29..2020-07-05).
        


## Code changes in the 'develop' branch


### Back office
* [#19882](https://github.com/PrestaShop/PrestaShop/pull/19882): Remove duplicated info_outline icon in stock alert. Thank you [@PululuK](https://github.com/PululuK)


### Installer
* [#19791](https://github.com/PrestaShop/PrestaShop/pull/19791): Allow user to choose to enable SSL or not in install process, by [@Progi1984](https://github.com/Progi1984)


## Code changes in the '1.7.7.x' branch


### Back office
* [#19929](https://github.com/PrestaShop/PrestaShop/pull/19929): Fixes the import configuration save, by [@Progi1984](https://github.com/Progi1984)
* [#17399](https://github.com/PrestaShop/PrestaShop/pull/17399): Expand Categories search capabilities for categories listing home page and avoid going from subcategory to root category when using grid filters, by [@matks](https://github.com/matks)


### Tests
* [#20046](https://github.com/PrestaShop/PrestaShop/pull/20046): Functional tests - Do not skip steps in CRUD category and subcategory scenario, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#19983](https://github.com/PrestaShop/PrestaShop/pull/19983): Functional tests - Update playwright version. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)


## Code changes in the '1.7.6.x' branch


### Core
* [#20018](https://github.com/PrestaShop/PrestaShop/pull/20018): Remove COLLATION placeholder from 1.7.6.6.sql, by [@matks](https://github.com/matks)
* [#19986](https://github.com/PrestaShop/PrestaShop/pull/19986): Fix php7-only code into 1766, by [@matks](https://github.com/matks)


### Back office
* [#19990](https://github.com/PrestaShop/PrestaShop/pull/19990): Fix BO page Module permission checks, by [@jolelievre](https://github.com/jolelievre)


### Front office
* [#20052](https://github.com/PrestaShop/PrestaShop/pull/20052): Fix product page event theme sided not getting fired, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#19979](https://github.com/PrestaShop/PrestaShop/pull/19979): Update outdated assets in 176x, by [@matks](https://github.com/matks)


## Code changes in modules, themes & tools


### Changes in developer documentation
* [#616](https://github.com/PrestaShop/docs/pull/616): Delete vertical padding of arrows to keep consistency, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#614](https://github.com/PrestaShop/docs/pull/614): Allow users to go on category page and click on arrow, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#611](https://github.com/PrestaShop/docs/pull/611): Add list of native modules, by [@eternoendless](https://github.com/eternoendless)
* [#609](https://github.com/PrestaShop/docs/pull/609): Add JS build into travis, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#595](https://github.com/PrestaShop/docs/pull/595): Add arrow on menu instead of going to page everytime you click, by [@NeOMakinG](https://github.com/NeOMakinG)


### Wishlist block
* [#44](https://github.com/PrestaShop/blockwishlist/pull/44): Add configuration. Thank you [@zalexki](https://github.com/zalexki)


### Nightly board
* [#38](https://github.com/PrestaShop/nightly-board/pull/38): Add campaign and browser to report detail, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#37](https://github.com/PrestaShop/nightly-board/pull/37): Add tooltips on some informations, by [@NeOMakinG](https://github.com/NeOMakinG)


### OnBoarding
* [#65](https://github.com/PrestaShop/welcome/pull/65): Use preprend-autoloader in composer.json, by [@matks](https://github.com/matks)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@NeOMakinG](https://github.com/NeOMakinG), [@boubkerbribri](https://github.com/boubkerbribri), [@matks](https://github.com/matks), [@eternoendless](https://github.com/eternoendless), [@zalexki](https://github.com/zalexki), [@jolelievre](https://github.com/jolelievre), [@nesrineabdmouleh](https://github.com/nesrineabdmouleh), [@Progi1984](https://github.com/Progi1984), [@PululuK](https://github.com/PululuK)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

---
layout: post
aliases: ["/news/coreweekly-32-2020"]
title:  "PrestaShop Core Weekly - Week 32 of 2020"
subtitle: "An inside look at the PrestaShop codebase"
date:   2020-08-10
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
twitter_image: /assets/images/theme/banner-core-weekly.jpg
icon: icon-calendar
tags:
 - core-monthly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 3th to Sunday 9th of August 2020.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)


## Releases

* [Ps_customersignin](https://github.com/PrestaShop/ps_customersignin): [v2.0.2](https://github.com/PrestaShop/ps_customersignin/releases/tag/v2.0.2)

## A quick update about PrestaShop's GitHub issues and pull requests:

- [54 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2020-08-03..2020-08-09) have been created in the project repositories;
- [42 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2020-08-03..2020-08-09), including [11 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2020-08-03..2020-08-09) on the core;
- [65 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2020-08-03..2020-08-09) in the project repositories;
- [46 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2020-08-03..2020-08-09), including [42 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2020-08-03..2020-08-09).



## Code changes in the 'develop' branch


### Core
* [#20472](https://github.com/PrestaShop/PrestaShop/pull/20472): Remove overwritten property: context. Thank you [@davidglezz](https://github.com/davidglezz)
* [#20383](https://github.com/PrestaShop/PrestaShop/pull/20383): Clean a bit PaymentModule class, by [@matks](https://github.com/matks)
* [#20366](https://github.com/PrestaShop/PrestaShop/pull/20366): Prevent deleting address being used in the cart. Thank you [@dariusakafest](https://github.com/dariusakafest)


### Back office
* [#20483](https://github.com/PrestaShop/PrestaShop/pull/20483): Typo error in AdminRequestSqlController.php. Thank you [@Amit-Kumar-Tiwari-Webkul](https://github.com/Amit-Kumar-Tiwari-Webkul)
* [#20475](https://github.com/PrestaShop/PrestaShop/pull/20475): Typo Error in AdminOutstandingController.php. Thank you [@Amit-Kumar-Tiwari-Webkul](https://github.com/Amit-Kumar-Tiwari-Webkul)
* [#20299](https://github.com/PrestaShop/PrestaShop/pull/20299): Add UpdateProductSuppliers command. Thank you [@zuk3975](https://github.com/zuk3975)


### Front office
* [#20474](https://github.com/PrestaShop/PrestaShop/pull/20474): [FO] : Wrong base price in Invoice. Thank you [@Amit-Kumar-Tiwari-Webkul](https://github.com/Amit-Kumar-Tiwari-Webkul)
* [#20410](https://github.com/PrestaShop/PrestaShop/pull/20410): Replace index.php?controller=404 by pagenotfound. Thank you [@Sinepel](https://github.com/Sinepel)


### Tests
* [#20427](https://github.com/PrestaShop/PrestaShop/pull/20427): Refactor behats ProductFeatureContext to multiple smaller contexts. Thank you [@zuk3975](https://github.com/zuk3975)


### Merge
* [#20500](https://github.com/PrestaShop/PrestaShop/pull/20500): Merge 177x into develop, by [@matks](https://github.com/matks)


## Code changes in the '1.7.7.x' branch


### Core
* [#20408](https://github.com/PrestaShop/PrestaShop/pull/20408): Fix bug on Invoices tax detail , by [@matthieu-rolland](https://github.com/matthieu-rolland)


### Back office
* [#20461](https://github.com/PrestaShop/PrestaShop/pull/20461): Fixed Modal "View pack content", by [@Progi1984](https://github.com/Progi1984)
* [#20457](https://github.com/PrestaShop/PrestaShop/pull/20457): Include product name and employee name in out of stock email. Thank you [@ks129](https://github.com/ks129)
* [#20433](https://github.com/PrestaShop/PrestaShop/pull/20433): Dont show root category on category grid search results, by [@matks](https://github.com/matks)


### Tests
* [#20468](https://github.com/PrestaShop/PrestaShop/pull/20468): Functional tests - Search hook in Positions page. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#20460](https://github.com/PrestaShop/PrestaShop/pull/20460): Functional tests - Update test filter categories, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#20459](https://github.com/PrestaShop/PrestaShop/pull/20459): Functional tests - Add new test 'Select default Theme', by [@boubkerbribri](https://github.com/boubkerbribri)
* [#20450](https://github.com/PrestaShop/PrestaShop/pull/20450): Functional tests - Update linkchecker urls, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#20440](https://github.com/PrestaShop/PrestaShop/pull/20440): Functional tests - Enable using loginCommon with different user than default one, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#20439](https://github.com/PrestaShop/PrestaShop/pull/20439): Functional tests - Avoid 'home' as new category to create, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#20418](https://github.com/PrestaShop/PrestaShop/pull/20418): Functional tests - Add tests for titles page, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#20394](https://github.com/PrestaShop/PrestaShop/pull/20394): Functional tests - Add test 'Search customers in create order page', by [@boubkerbribri](https://github.com/boubkerbribri)
* [#20302](https://github.com/PrestaShop/PrestaShop/pull/20302): Functional tests - Add update a language. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)


## Code changes in modules, themes & tools


### Nightly board
* [#43](https://github.com/PrestaShop/nightly-board/pull/43): Change placeholder of search to EN, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#42](https://github.com/PrestaShop/nightly-board/pull/42): Move suite informations and adapt report informations on mobile, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#41](https://github.com/PrestaShop/nightly-board/pull/41): Fix some styles on suite topbar, by [@NeOMakinG](https://github.com/NeOMakinG)


### Visits and Visitors module
* [#12](https://github.com/PrestaShop/statsvisits/pull/12): Bump version to 2.0.3, by [@Progi1984](https://github.com/Progi1984)


### PrestaShop Specifications
* [#123](https://github.com/PrestaShop/prestashop-specs/pull/123): Update CONTRIBUTING.md. Thank you [@MatShir](https://github.com/MatShir)


### Changes in developer documentation
* [#656](https://github.com/PrestaShop/docs/pull/656): Add search hooks, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#654](https://github.com/PrestaShop/docs/pull/654): Fix wrong compatibility note, by [@eternoendless](https://github.com/eternoendless)
* [#651](https://github.com/PrestaShop/docs/pull/651): Update some links. Thank you [@justeen35](https://github.com/justeen35)
* [#650](https://github.com/PrestaShop/docs/pull/650): Fix broken link in Smarty extensions page. Thank you [@bruce-thomas](https://github.com/bruce-thomas)


### Product Comments module
* [#67](https://github.com/PrestaShop/productcomments/pull/67): Update version to 4.1.0, by [@Progi1984](https://github.com/Progi1984)


### Prestashop UI Kit
* [#100](https://github.com/PrestaShop/prestashop-ui-kit/pull/100): Delete useless dist folders, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#99](https://github.com/PrestaShop/prestashop-ui-kit/pull/99): Push assets on develop and show toasts by default, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#98](https://github.com/PrestaShop/prestashop-ui-kit/pull/98): Bump elliptic from 6.5.2 to 6.5.3. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### Wishlist block module
* [#78](https://github.com/PrestaShop/blockwishlist/pull/78): Fix php translate typo, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#76](https://github.com/PrestaShop/blockwishlist/pull/76): Avoid negative or zero values as quantity, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Stylelint configuration
* [#3](https://github.com/PrestaShop/stylelint-config/pull/3): Add stylelint-no-unsupported-browser-features, by [@NeOMakinG](https://github.com/NeOMakinG)


### Webservices PHP Client
* [#68](https://github.com/PrestaShop/PrestaShop-webservice-lib/pull/68): Add 'language' support to resources. Thank you [@aquiandres](https://github.com/aquiandres)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@NeOMakinG](https://github.com/NeOMakinG), [@matks](https://github.com/matks), [@Progi1984](https://github.com/Progi1984), [@Amit-Kumar-Tiwari-Webkul](https://github.com/Amit-Kumar-Tiwari-Webkul), [@davidglezz](https://github.com/davidglezz), [@nesrineabdmouleh](https://github.com/nesrineabdmouleh), [@MatShir](https://github.com/MatShir), [@boubkerbribri](https://github.com/boubkerbribri), [@ks129](https://github.com/ks129), [@eternoendless](https://github.com/eternoendless), [@justeen35](https://github.com/justeen35), [@zuk3975](https://github.com/zuk3975), [@bruce-thomas](https://github.com/bruce-thomas), [@Sinepel](https://github.com/Sinepel), [@matthieu-rolland](https://github.com/matthieu-rolland), [@Quetzacoalt91](https://github.com/Quetzacoalt91), [@dependabot[bot]](https://github.com/apps/dependabot), [@dariusakafest](https://github.com/dariusakafest), [@aquiandres](https://github.com/aquiandres), [@SalarNazar](https://github.com/SalarNazar)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

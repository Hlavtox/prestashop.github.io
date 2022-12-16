---
layout: post
aliases: ["/news/coreweekly-week-09-2020"]
title:  "PrestaShop Core Weekly - Week 9 of 2020"
subtitle: "An inside look at the PrestaShop codebase"
date:   2020-03-02
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 24th of February to Sunday 1st of March 2020.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)

## General messages

Dear developers,

Since last week, multiple release processes have started :

Next patch version for 1.7.6.x (v1.7.6.4) is now complete, QA team will test the build this week.

Next PS 1.7 minor version (v1.7.7.0) is now frozen ! 🎉️ ☃️

A quick look at the work done on 1.7.7:

- [196 issues have been fixed](https://github.com/PrestaShop/PrestaShop/issues?page=6&q=is%3Aissue+milestone%3A1.7.7.0+is%3Aclosed+label%3ABug+label%3AFixed)
- [796 pull requests have been merged](https://github.com/PrestaShop/PrestaShop/pulls?utf8=%E2%9C%93&q=is%3Apr+milestone%3A1.7.7.0+is%3Amerged+)

What a huge amount of work!

This version is currently under heavy testing by the QA team. Following the tests report, we will fix all major issues in order to be able to deliver a Beta 1.7.7.0 build.

## A quick update about PrestaShop's GitHub issues and pull requests:

- [70 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2020-02-24..2020-03-01) have been created in the project repositories;
- [64 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2020-02-24..2020-03-01), including [6 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2020-02-24..2020-03-01) on the core;
- [93 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2020-02-24..2020-03-01) in the project repositories;
- [106 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2020-02-24..2020-03-01), including [72 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2020-02-24..2020-03-01)


## Code changes in the 'develop' branch


### Core
* [#17785](https://github.com/PrestaShop/PrestaShop/pull/17785): Fix X-Forwarded-For not supported properly. Thank you [@davidglezz](https://github.com/davidglezz)


## Code changes in the '1.7.7.x' branch (for v1.7.7.0)


### Back office
* [#17884](https://github.com/PrestaShop/PrestaShop/pull/17884): Use constant for reduction type in CatalogPriceRuleGridDataFactory. Thank you [@zuk3975](https://github.com/zuk3975)
* [#17796](https://github.com/PrestaShop/PrestaShop/pull/17796): Fix new wording without domain, by [@eternoendless](https://github.com/eternoendless)
* [#17752](https://github.com/PrestaShop/PrestaShop/pull/17752): Add Prev/Next order button in the Order page. Thank you [@tdavidsonas88](https://github.com/tdavidsonas88)


### Tests
* [#17872](https://github.com/PrestaShop/PrestaShop/pull/17872): Functional tests - Invoices > Other options - delete check legal free text from scenario. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#17836](https://github.com/PrestaShop/PrestaShop/pull/17836): Funtional tests - Fix employee faker, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#17829](https://github.com/PrestaShop/PrestaShop/pull/17829): Functional tests - Shop Parameters> General enable/disable display brands. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#17828](https://github.com/PrestaShop/PrestaShop/pull/17828): Functional tests - Shop Parameters> General enable/disable display suppliers. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#17824](https://github.com/PrestaShop/PrestaShop/pull/17824): Functional tests - Fix sending emails in nightly, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#17795](https://github.com/PrestaShop/PrestaShop/pull/17795): Functional tests - Payment>Preferences Configure currency restriction. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#17779](https://github.com/PrestaShop/PrestaShop/pull/17779): Functional tests - Add new tests 'Sort categories' and 'Change category position', by [@boubkerbribri](https://github.com/boubkerbribri)
* [#17775](https://github.com/PrestaShop/PrestaShop/pull/17775): Functional tests - Customer settings enable/disable send email after registration. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#17772](https://github.com/PrestaShop/PrestaShop/pull/17772): Functional tests - Add test 'Sort Addresses', by [@boubkerbribri](https://github.com/boubkerbribri)
* [#17762](https://github.com/PrestaShop/PrestaShop/pull/17762): Functional tests - Add test 'Import localization pack', by [@boubkerbribri](https://github.com/boubkerbribri)
* [#17754](https://github.com/PrestaShop/PrestaShop/pull/17754): Functional tests - Product settings display remaining quantity in product page. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#17746](https://github.com/PrestaShop/PrestaShop/pull/17746): Restore GA for PHP CS Fixer, by [@matks](https://github.com/matks)
* [#17699](https://github.com/PrestaShop/PrestaShop/pull/17699): Functional Tests - Product settings choose quantity discounts based on. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)


## Code changes in the '1.7.6.x' branch (for v1.7.6.4)


### Core
* [#17846](https://github.com/PrestaShop/PrestaShop/pull/17846): Fix exception thrown when editing a customer with a bad email address, by [@atomiix](https://github.com/atomiix)


### Back office
* [#17711](https://github.com/PrestaShop/PrestaShop/pull/17711): Fix a bug on safari where SEO preview on create page was not updated, by [@NeOMakinG](https://github.com/NeOMakinG)


## Code changes in modules, themes & tools


### Changes in developer documentation
* [#474](https://github.com/PrestaShop/docs/pull/474): Update theme translation documentation, by [@eternoendless](https://github.com/eternoendless)
* [#473](https://github.com/PrestaShop/docs/pull/473): Update allowed licenses for modules, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#470](https://github.com/PrestaShop/docs/pull/470): Improve guidelines, by [@eternoendless](https://github.com/eternoendless)
* [#468](https://github.com/PrestaShop/docs/pull/468): Fix bad LayoutInterface namespace. Thank you [@dheerajwebkul](https://github.com/dheerajwebkul)
* [#463](https://github.com/PrestaShop/docs/pull/463): Add a definition of what is a module compatible multistore, by [@marionf](https://github.com/marionf)
* [#461](https://github.com/PrestaShop/docs/pull/461): Add a paragraph about compatible licenses, by [@ttoine](https://github.com/ttoine)


### Share Buttons module
* [#34](https://github.com/PrestaShop/ps_sharebuttons/pull/34): Replace http with https for socials URLs, by [@khouloudbelguith](https://github.com/khouloudbelguith)
* [#32](https://github.com/PrestaShop/ps_sharebuttons/pull/32): Clean license headers and readme, by [@matks](https://github.com/matks)
* [#31](https://github.com/PrestaShop/ps_sharebuttons/pull/31): Update readme to add multistore compatibility, by [@marionf](https://github.com/marionf)
* [#30](https://github.com/PrestaShop/ps_sharebuttons/pull/30): Bump to version 2.1.0, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#21](https://github.com/PrestaShop/ps_sharebuttons/pull/21): Multiline whitespace before semicolons. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#18](https://github.com/PrestaShop/ps_sharebuttons/pull/18): Short array syntax. Thank you [@MathiasReker](https://github.com/MathiasReker)


### Prestonbot
* [#91](https://github.com/PrestaShop/prestonbot/pull/91): Fix unexpected label creation, by [@eternoendless](https://github.com/eternoendless)

### Block Reassurance module
* [#42](https://github.com/PrestaShop/blockreassurance/pull/42): Fix bad license header for CategoryFetcher.php, by [@matks](https://github.com/matks)
* [#41](https://github.com/PrestaShop/blockreassurance/pull/41): Update readme to add multistore compatibility, by [@marionf](https://github.com/marionf)
* [#38](https://github.com/PrestaShop/blockreassurance/pull/38): Add Symfony 5 support. Thank you [@mvorisek](https://github.com/mvorisek)

## About Multistore compatibility

Product Team member [@marionf](https://github.com/marionf) spent [a lot of time](https://github.com/PrestaShop/docs/pull/463) working on the topic "What means 'a module is multistore compatible' ?" and went through all of native PrestaShop modules to clarify their status and wrote it into the README.md of these modules (see for example the [Block Reassurance module](https://github.com/PrestaShop/blockreassurance/pull/41/files)).


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@eternoendless](https://github.com/eternoendless), [@khouloudbelguith](https://github.com/khouloudbelguith), [@Quetzacoalt91](https://github.com/Quetzacoalt91), [@zuk3975](https://github.com/zuk3975), [@nesrineabdmouleh](https://github.com/nesrineabdmouleh), [@atomiix](https://github.com/atomiix), [@boubkerbribri](https://github.com/boubkerbribri), [@marionf](https://github.com/marionf), [@matks](https://github.com/matks), [@davidglezz](https://github.com/davidglezz), [@dheerajwebkul](https://github.com/dheerajwebkul), [@jolelievre](https://github.com/jolelievre), [@tdavidsonas88](https://github.com/tdavidsonas88), [@ttoine](https://github.com/ttoine), [@NeOMakinG](https://github.com/NeOMakinG), [@PierreRambaud](https://github.com/PierreRambaud), [@mvorisek](https://github.com/mvorisek), [@MathiasReker](https://github.com/MathiasReker)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!


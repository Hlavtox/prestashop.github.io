---
layout: post
aliases: ["/news/coreweekly-week-06-2020"]
title:  "PrestaShop Core Weekly - Week 6 of 2020"
subtitle: "An inside look at the PrestaShop codebase"
date:   2020-02-11
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 3rd to Sunday 9th of February 2020.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)


## A quick update about PrestaShop's GitHub issues and pull requests:

- [64 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2020-02-03..2020-02-09) have been created in the project repositories;
- [74 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2020-02-03..2020-02-09), including [16 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2020-02-03..2020-02-09) on the core;
- [54 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2020-02-03..2020-02-09) in the project repositories;
- [52 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2020-02-03..2020-02-09), including [39 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2020-02-03..2020-02-09).



## Code changes in the 'develop' branch


### Core
* [#17515](https://github.com/PrestaShop/PrestaShop/pull/17515): Increase timeout to download translation packages from 5 to 20 seconds, by [@eternoendless](https://github.com/eternoendless)
* [#17510](https://github.com/PrestaShop/PrestaShop/pull/17510): Fix phpdoc of class Link, by [@Matt75](https://github.com/Matt75)
* [#15773](https://github.com/PrestaShop/PrestaShop/pull/15773): CO : Performance optimisation. Thank you [@djbuch](https://github.com/djbuch)


### Front office
* [#17133](https://github.com/PrestaShop/PrestaShop/pull/17133): Correct history on product page, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#17073](https://github.com/PrestaShop/PrestaShop/pull/17073): Email subject doesn't support html entities. Thank you [@jf-viguier](https://github.com/jf-viguier)
* [#17020](https://github.com/PrestaShop/PrestaShop/pull/17020): Sending rating event on product refresh to avoid empty rating stars, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#17014](https://github.com/PrestaShop/PrestaShop/pull/17014): Correct history problem on listing page, by [@NeOMakinG](https://github.com/NeOMakinG)


### Tests
* [#17533](https://github.com/PrestaShop/PrestaShop/pull/17533): Only compute assets for Travis for tests which need it, by [@matks](https://github.com/matks)


### Merge
* [#17545](https://github.com/PrestaShop/PrestaShop/pull/17545): Merge 1.7.7.x into develop - 07/02/2020, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#17483](https://github.com/PrestaShop/PrestaShop/pull/17483): Merge 1.7.7.x into develop - 03/02/2020, by [@matks](https://github.com/matks)


## Code changes in the '1.7.7.x' branch (for v1.7.7.0)


### Core
* [#17537](https://github.com/PrestaShop/PrestaShop/pull/17537): Increase timeout to download translation packages from 5 to 20 seconds, by [@jolelievre](https://github.com/jolelievre)


### Back office
* [#17547](https://github.com/PrestaShop/PrestaShop/pull/17547): Fix grids, when search finds no result we still display filters and reset button, by [@matks](https://github.com/matks)
* [#17531](https://github.com/PrestaShop/PrestaShop/pull/17531): Remove irrelevant Todo in order messages. Thank you [@zuk3975](https://github.com/zuk3975)
* [#17478](https://github.com/PrestaShop/PrestaShop/pull/17478): Cherry picked the changes from develop related to Refactor UI kit form #16964 and applied to 1.7.7.x. Thank you [@tdavidsonas88](https://github.com/tdavidsonas88)
* [#17465](https://github.com/PrestaShop/PrestaShop/pull/17465): Fix create order customization/combinations, by [@atomiix](https://github.com/atomiix)
* [#17456](https://github.com/PrestaShop/PrestaShop/pull/17456): Introduces checkbox in list filter row. Thank you [@tomas862](https://github.com/tomas862)
* [#17448](https://github.com/PrestaShop/PrestaShop/pull/17448): Fix create order info missing, by [@atomiix](https://github.com/atomiix)
* [#17445](https://github.com/PrestaShop/PrestaShop/pull/17445): Fix wrong address edit link, by [@atomiix](https://github.com/atomiix)
* [#17444](https://github.com/PrestaShop/PrestaShop/pull/17444): Change tinymce lang when changeLanguage event is fired, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#17421](https://github.com/PrestaShop/PrestaShop/pull/17421): Delete free shipping voucher after creating an order on BO. Thank you [@zuk3975](https://github.com/zuk3975)
* [#17416](https://github.com/PrestaShop/PrestaShop/pull/17416): Migrate standard refund and return products in order page, by [@jolelievre](https://github.com/jolelievre)
* [#17366](https://github.com/PrestaShop/PrestaShop/pull/17366): Added missing admin security annotations. Thank you [@RaimondasSapola](https://github.com/RaimondasSapola)
* [#17241](https://github.com/PrestaShop/PrestaShop/pull/17241): Do not allow negative amount in order payment block, by [@atomiix](https://github.com/atomiix)


### Tests
* [#17559](https://github.com/PrestaShop/PrestaShop/pull/17559): Functional tests - Fix select all grid selector, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#17532](https://github.com/PrestaShop/PrestaShop/pull/17532): Fix PHP CS Fixer configuration: disable single_line_throw and backport #17328, by [@matks](https://github.com/matks)
* [#17518](https://github.com/PrestaShop/PrestaShop/pull/17518): Functional test - Add data file for module categories, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#17499](https://github.com/PrestaShop/PrestaShop/pull/17499): Functional tests - Add new test Filter modules by categories, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#17495](https://github.com/PrestaShop/PrestaShop/pull/17495): Functional tests - Add test for monitoring product without description, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#17440](https://github.com/PrestaShop/PrestaShop/pull/17440): Functional tests - Add new test bulk actions languages, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#17388](https://github.com/PrestaShop/PrestaShop/pull/17388): Functional tests - Product settings test new days number. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)


## Code changes in the '1.7.6.x' branch (for v1.7.6.4)


### Back office
* [#17395](https://github.com/PrestaShop/PrestaShop/pull/17395): Can't explore a category when all subcats are disabled. Thank you [@PululuK](https://github.com/PululuK)


## Code changes in modules, themes & tools


### Classic-rocket theme
* [#134](https://github.com/PrestaShop/classic-rocket/pull/134): Remove forgotten </li> closing tag. Thank you [@micka-fdz](https://github.com/micka-fdz)
* [#132](https://github.com/PrestaShop/classic-rocket/pull/132): Rework of .custom-file translations. Thank you [@micka-fdz](https://github.com/micka-fdz)


### Core Weekly Generator tool
* [#24](https://github.com/PrestaShop/core-weekly-generator/pull/24): Add new core team member, by [@ttoine](https://github.com/ttoine)


### QA nightly results
* [#19](https://github.com/PrestaShop/QANightlyResults/pull/19): Add comparison, by [@SimonGrn](https://github.com/SimonGrn)


### PrestaShop Specifications
* [#84](https://github.com/PrestaShop/prestashop-specs/pull/84): Create Product Setting Page.md. Thank you [@MatShir](https://github.com/MatShir)
* [#79](https://github.com/PrestaShop/prestashop-specs/pull/79): Created a first version of specs template. Thank you [@sam-pires](https://github.com/sam-pires)


### Theme Custo module
* [#20](https://github.com/PrestaShop/ps_themecusto/pull/20): Check if file exists before requiring it, by [@atomiix](https://github.com/atomiix)


### Product Comments module
* [#48](https://github.com/PrestaShop/productcomments/pull/48): Listening event on product refresh to construct stars again, by [@NeOMakinG](https://github.com/NeOMakinG)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@boubkerbribri](https://github.com/boubkerbribri), [@matks](https://github.com/matks), [@NeOMakinG](https://github.com/NeOMakinG), [@jolelievre](https://github.com/jolelievre), [@zuk3975](https://github.com/zuk3975), [@micka-fdz](https://github.com/micka-fdz), [@eternoendless](https://github.com/eternoendless), [@Matt75](https://github.com/Matt75), [@ttoine](https://github.com/ttoine), [@SimonGrn](https://github.com/SimonGrn), [@tdavidsonas88](https://github.com/tdavidsonas88), [@atomiix](https://github.com/atomiix), [@MatShir](https://github.com/MatShir), [@tomas862](https://github.com/tomas862), [@PululuK](https://github.com/PululuK), [@nesrineabdmouleh](https://github.com/nesrineabdmouleh), [@RaimondasSapola](https://github.com/RaimondasSapola), [@jf-viguier](https://github.com/jf-viguier), [@sam-pires](https://github.com/sam-pires), [@djbuch](https://github.com/djbuch)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!


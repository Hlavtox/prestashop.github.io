---
layout: post
aliases: ["/news/coreweekly-week-24-2019"]
title:  "PrestaShop Core Weekly - Week 24 of 2019"
subtitle: "An inside look at the PrestaShop codebase"
date:   2019-06-17 17:30:00
authors: [ AntoineThomas ]
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 10th to Sunday 16th of June 2019.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)


## General messages

Dear Developers,

While the last bugs and regressions are being fixed on the core in order to build a release candidate, you will notice that a lot of work has been done on modules too! And new versions of very popular native modules are coming :-)

Stay tune for the release candidate.

And of course, tomorrow, don't forget to join the PrestaShop team and partners at [the Madrid event](https://www.prestashop.com/es/eventos/prestashop-day-madrid).


## A quick update about PrestaShop's GitHub issues and pull requests:

- [65 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2019-06-10..2019-06-16) have been created in the project repositories;
- [61 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2019-06-10..2019-06-16), including [18 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2019-06-10..2019-06-16) on the core;
- [81 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2019-06-10..2019-06-16) in the project repositories;
- [62 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2019-06-10..2019-06-16), including [52 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2019-06-10..2019-06-16).

## Code changes in the 'develop' branch

### Core

* [#14130](https://github.com/PrestaShop/PrestaShop/pull/14130): Merge 1.7.6.x to develop - 10/06/2019 [travis investigation - dont merge/close], by [@matks](https://github.com/matks)
* [#14133](https://github.com/PrestaShop/PrestaShop/pull/14133): Merge 1.7.6.x to develop - 10/06/2019, by [@matks](https://github.com/matks)
* [#14165](https://github.com/PrestaShop/PrestaShop/pull/14165): Fix phpdoc on module stuffs, by [@Matt75](https://github.com/Matt75)
* [#14178](https://github.com/PrestaShop/PrestaShop/pull/14178): Merge 1.7.6.x to develop - 12/06/2019, by [@matks](https://github.com/matks)
* [#14192](https://github.com/PrestaShop/PrestaShop/pull/14192): Merge 1.7.6.x to develop - 13/06/2019 , by [@matks](https://github.com/matks)


## Code changes in the "1.7.6.x" branch (for v1.7.6.0)

### Core

* [#13919](https://github.com/PrestaShop/PrestaShop/pull/13919): Tax must be returned depending on PS_TAX_DISPLAY only, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#13923](https://github.com/PrestaShop/PrestaShop/pull/13923): Make sure index exist before getting value for gift message, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#14134](https://github.com/PrestaShop/PrestaShop/pull/14134): Combine consecutive issets(), by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Back office

* [#13869](https://github.com/PrestaShop/PrestaShop/pull/13869): Extract theme folder scanning into an external class FolderThemeScanner, by [@jolelievre](https://github.com/jolelievre)
* [#13971](https://github.com/PrestaShop/PrestaShop/pull/13971): Update AdminStatsController.php. Thank you [@ComonSoft](https://github.com/ComonSoft)
* [#13984](https://github.com/PrestaShop/PrestaShop/pull/13984): Fix bo categories, by [@jolelievre](https://github.com/jolelievre)
* [#14084](https://github.com/PrestaShop/PrestaShop/pull/14084): Fixes updating name and symbol for currency. Thank you [@sarjon](https://github.com/sarjon)
* [#14101](https://github.com/PrestaShop/PrestaShop/pull/14101): Fix missing permission roles. Thank you [@202-ecommerce](https://github.com/202-ecommerce)
* [#14107](https://github.com/PrestaShop/PrestaShop/pull/14107): Do not allow the selection of any subcategories, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#14137](https://github.com/PrestaShop/PrestaShop/pull/14137): Adds missing form_rest in Shop Parameters > Preferences. Thank you [@zuk3975](https://github.com/zuk3975)
* [#14152](https://github.com/PrestaShop/PrestaShop/pull/14152): Adjust employee avatar size. Thank you [@zuk3975](https://github.com/zuk3975)
* [#14156](https://github.com/PrestaShop/PrestaShop/pull/14156): Add missing null check in EditCmsPageHandler. Thank you [@zuk3975](https://github.com/zuk3975)
* [#14172](https://github.com/PrestaShop/PrestaShop/pull/14172): Add missing form_errors for identifiable object forms. Thank you [@sarjon](https://github.com/sarjon)
* [#14189](https://github.com/PrestaShop/PrestaShop/pull/14189): Fix manufacturer controller using wrong DomainException ns. Thank you [@zuk3975](https://github.com/zuk3975)


### Front office

* [#13370](https://github.com/PrestaShop/PrestaShop/pull/13370): Fix cart refresh after voucher removal, by [@matks](https://github.com/matks)
* [#14075](https://github.com/PrestaShop/PrestaShop/pull/14075): Fix: If Ask for birth date option is disabled, an exception is displayed in the FO. Thank you [@OneDotIT](https://github.com/OneDotIT)
* [#14138](https://github.com/PrestaShop/PrestaShop/pull/14138): Add comment in Customer registration form, add better error message, by [@jolelievre](https://github.com/jolelievre)
* [#14163](https://github.com/PrestaShop/PrestaShop/pull/14163): Add missing quotes in error message, by [@jolelievre](https://github.com/jolelievre)
* [#14166](https://github.com/PrestaShop/PrestaShop/pull/14166): Fix categories cover images which had an incorrect format, by [@jolelievre](https://github.com/jolelievre)
* [#14180](https://github.com/PrestaShop/PrestaShop/pull/14180): Improve right block on cart and checkout page, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#14190](https://github.com/PrestaShop/PrestaShop/pull/14190): You need to be authenticated to play with addresses, by [@PierreRambaud](https://github.com/PierreRambaud)


### Tests

* [#13773](https://github.com/PrestaShop/PrestaShop/pull/13773): Fix international tests. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#13953](https://github.com/PrestaShop/PrestaShop/pull/13953): Fixing and moving tests design from broken to suite full, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#14151](https://github.com/PrestaShop/PrestaShop/pull/14151): Force disabling debug mode, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#14196](https://github.com/PrestaShop/PrestaShop/pull/14196): Last tests fixes (page migration, language settings), by [@SimonGrn](https://github.com/SimonGrn)
* [#14222](https://github.com/PrestaShop/PrestaShop/pull/14222): Fix steps for Virtual product, by [@boubkerbribri](https://github.com/boubkerbribri)


## Code changes in modules, themes & tools

### Translation tools bundle

* [#61](https://github.com/PrestaShop/TranslationToolsBundle/pull/61): Handle weird node parsing, by [@matks](https://github.com/matks)
* [#63](https://github.com/PrestaShop/TranslationToolsBundle/pull/63): Improve test sample and empty arg check in node parser, by [@matks](https://github.com/matks)


### Auto upgrade

* [#320](https://github.com/PrestaShop/autoupgrade/pull/320): Add action option in command line upgrade doc, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Circuit Breaker

* [#31](https://github.com/PrestaShop/circuit-breaker/pull/31): Introduce more generic AdvancedCircuitBreaker, by [@jolelievre](https://github.com/jolelievre)
* [#33](https://github.com/PrestaShop/circuit-breaker/pull/33): Update Readme, add release-drafter config, by [@jolelievre](https://github.com/jolelievre)
* [#34](https://github.com/PrestaShop/circuit-breaker/pull/34): Merge develop to master for v3.0.0, by [@jolelievre](https://github.com/jolelievre)
* [#35](https://github.com/PrestaShop/circuit-breaker/pull/35): Fix a few errors reported by phpqa, by [@jolelievre](https://github.com/jolelievre)
* [#36](https://github.com/PrestaShop/circuit-breaker/pull/36): Fix psalm, by [@jolelievre](https://github.com/jolelievre)


### Faceted search

* [#86](https://github.com/PrestaShop/ps_facetedsearch/pull/86): Do not erase filter when multiple selection is not accepted, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#87](https://github.com/PrestaShop/ps_facetedsearch/pull/87): Make features great again, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#88](https://github.com/PrestaShop/ps_facetedsearch/pull/88): Select on multishop table instead product table, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#89](https://github.com/PrestaShop/ps_facetedsearch/pull/89): fix bug indexed prices. Thank you [@hafkhami](https://github.com/hafkhami)
* [#90](https://github.com/PrestaShop/ps_facetedsearch/pull/90): Price indexing stopped working on PS1.7.5, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#91](https://github.com/PrestaShop/ps_facetedsearch/pull/91): Bump to 3.0.4, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#92](https://github.com/PrestaShop/ps_facetedsearch/pull/92): Release version 3.0.4, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#93](https://github.com/PrestaShop/ps_facetedsearch/pull/93): Make sure initial population is reset, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#95](https://github.com/PrestaShop/ps_facetedsearch/pull/95): Typo. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#96](https://github.com/PrestaShop/ps_facetedsearch/pull/96): Lossless compression. Thank you [@MathiasReker](https://github.com/MathiasReker)


### Product comments

* [#33](https://github.com/PrestaShop/productcomments/pull/33): Improve addons block (with CircuitBreaker), by [@jolelievre](https://github.com/jolelievre)
* [#34](https://github.com/PrestaShop/productcomments/pull/34): Merge dev to master for v4.0.0, by [@jolelievre](https://github.com/jolelievre)


### Shopping cart

* [#20](https://github.com/PrestaShop/ps_shoppingcart/pull/20): Fix cart modal when a customized product is added to cart. Thank you [@unlocomqx](https://github.com/unlocomqx)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: @202-ecommerce, @ComonSoft, @OneDotIT, @sarjon, @unlocomqx, @zuk3975!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

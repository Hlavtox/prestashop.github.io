---
layout: post
aliases: ["/news/coreweekly-week-31-2019"]
title:  "PrestaShop Core Weekly - Week 31 of 2019"
subtitle: "An inside look at the PrestaShop codebase"
date:   2019-08-01 16:30:00
authors: [ AntoineThomas ]
image: /assets/images/2017/04/core_weekly_banner.jpg
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 29th of July to Sunday 04th of August 2019.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)


## General messages

Dear Developers,

Would you be interested to participate to Hacktoberfest 2019 with your contributions to the PrestaShop open source software? If yes, let's get in touch via the comments, the forums or via Twitter.

The best way to be prepared for Octocber: contribute your first pull request during the summer and learn how to do it well with the code review!


## A quick update about PrestaShop's GitHub issues and pull requests:

- [76 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2019-07-29..2019-08-04) have been created in the project repositories;
- [54 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2019-07-29..2019-08-04), including [11 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2019-07-29..2019-08-04) on the core;
- [46 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2019-07-29..2019-08-04) in the project repositories;
- [52 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2019-07-29..2019-08-04), including [35 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2019-07-29..2019-08-04).


## Code changes in the 'develop' branch

### Core

* [#13830](https://github.com/PrestaShop/PrestaShop/pull/13830): Remove duplicate var in cart.php. Thank you [@davidglezz](https://github.com/davidglezz)
* [#14601](https://github.com/PrestaShop/PrestaShop/pull/14601): Revert removed templates for mail dynamic contents, order mails mainl…, by [@jolelievre](https://github.com/jolelievre)
* [#14949](https://github.com/PrestaShop/PrestaShop/pull/14949): Update Module.php docs on version property type. Thank you [@zalexki](https://github.com/zalexki)


### Back office

* [#13730](https://github.com/PrestaShop/PrestaShop/pull/13730): Admin Specific Price : wrong display. Thank you [@123monsite-regis](https://github.com/123monsite-regis)
* [#14671](https://github.com/PrestaShop/PrestaShop/pull/14671): Make sure token is properly used in legacy context, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#14800](https://github.com/PrestaShop/PrestaShop/pull/14800): Add category to product CQRS command, by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#14872](https://github.com/PrestaShop/PrestaShop/pull/14872): Delete migrated AdminCmsController again, by [@matks](https://github.com/matks)


### Front office

* [#14786](https://github.com/PrestaShop/PrestaShop/pull/14786): Sprintf function broken in 1.7.6 for custom module templates. Thank you [@roja45](https://github.com/roja45)


### Tests

* [#14971](https://github.com/PrestaShop/PrestaShop/pull/14971): Trigger nightly report, by [@PierreRambaud](https://github.com/PierreRambaud)


### Web services

* [#14899](https://github.com/PrestaShop/PrestaShop/pull/14899): Initialize container in WebService environment (bis), by [@Progi1984](https://github.com/Progi1984)


## Code changes in the "1.7.6.x" branch (for v1.7.6.1)

### Core

* [#14711](https://github.com/PrestaShop/PrestaShop/pull/14711): Update Decimal library to 1.2.0, by [@eternoendless](https://github.com/eternoendless)
* [#14859](https://github.com/PrestaShop/PrestaShop/pull/14859): Move i18n.prestashop.net into https and remove unwanted file, by [@PierreRambaud](https://github.com/PierreRambaud)


### Back office

* [#14914](https://github.com/PrestaShop/PrestaShop/pull/14914): Date picker calendar is shown in wrong place when rendered downwards in grid, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#14926](https://github.com/PrestaShop/PrestaShop/pull/14926): Fix logs filtering. Thank you [@sarjon](https://github.com/sarjon)


### Front office

* [#14710](https://github.com/PrestaShop/PrestaShop/pull/14710): Make last breadcrumb element not clickable, by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#14863](https://github.com/PrestaShop/PrestaShop/pull/14863): Prevent uninstall of Product Comments module. Thank you [@templatin](https://github.com/templatin)
* [#14945](https://github.com/PrestaShop/PrestaShop/pull/14945): Fixed {firstname} typo in order customer comment mail in 1.7.6.x. Thank you [@dheerajwebkul](https://github.com/dheerajwebkul)


### Web services

* [#14953](https://github.com/PrestaShop/PrestaShop/pull/14953): Initialize container in WebService environment (Progi1984's work on 1.7.7), by [@matthieu-rolland](https://github.com/matthieu-rolland)


## Code changes in modules, themes & tools

### PrestaShop Specifications

* [#13](https://github.com/PrestaShop/prestashop-specs/pull/13): Update Catalog-products-add-edit-basic-settings.md, by [@marionf](https://github.com/marionf)
* [#14](https://github.com/PrestaShop/prestashop-specs/pull/14): Update Catalog-Products-add-edit-elements-in-all-tabs.md, by [@marionf](https://github.com/marionf)
* [#15](https://github.com/PrestaShop/prestashop-specs/pull/15): Update, by [@marionf](https://github.com/marionf)
* [#16](https://github.com/PrestaShop/prestashop-specs/pull/16): Update virtual product tab, by [@marionf](https://github.com/marionf)
* [#17](https://github.com/PrestaShop/prestashop-specs/pull/17): Update shipping tab, by [@marionf](https://github.com/marionf)


### Faceted search

* [#116](https://github.com/PrestaShop/ps_facetedsearch/pull/116): In faceted search, Manufacturers are displayed using ordering by id, instead of name, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#117](https://github.com/PrestaShop/ps_facetedsearch/pull/117): Remove unwanted curl, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#118](https://github.com/PrestaShop/ps_facetedsearch/pull/118): Repair collapse for sliders range, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#119](https://github.com/PrestaShop/ps_facetedsearch/pull/119): Number of product are not ok after selecting filters, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#120](https://github.com/PrestaShop/ps_facetedsearch/pull/120): Bump to 3.2.0, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#121](https://github.com/PrestaShop/ps_facetedsearch/pull/121): Release 3.2.0 , by [@PierreRambaud](https://github.com/PierreRambaud)


### PHP Coding Standards

* [#10](https://github.com/PrestaShop/php-coding-standards/pull/10): Add _PS_THEME_DIR_, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#11](https://github.com/PrestaShop/php-coding-standards/pull/11): Update bootstrap.php with another method for loading proper phpparser lib. Thank you [@zalexki](https://github.com/zalexki)
* [#12](https://github.com/PrestaShop/php-coding-standards/pull/12): Update constants in bootstrap.php. Thank you [@zalexki](https://github.com/zalexki)


### QA nightly results

* [#3](https://github.com/PrestaShop/QANightlyResults/pull/3): New insert system, by [@SimonGrn](https://github.com/SimonGrn)
* [#5](https://github.com/PrestaShop/QANightlyResults/pull/5): CSS tweaks, filename save, add GCP URL variable, add GA script, by [@SimonGrn](https://github.com/SimonGrn)
* [#6](https://github.com/PrestaShop/QANightlyResults/pull/6): update README with GCP URL, by [@SimonGrn](https://github.com/SimonGrn)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: @123monsite-regis, @davidglezz, @dheerajwebkul, @eternoendless, @jolelievre, @marionf, @matks, @matthieu-rolland, @PierreRambaud, @Progi1984, @Quetzacoalt91, @roja45, @sarjo, @SimonGrn, @templatin, @zalexki!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

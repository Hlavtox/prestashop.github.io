---
layout: post
aliases: ["/news/coreweekly-30-2021"]
title:  "PrestaShop Core Weekly - Week 30 of 2021"
subtitle: "An inside look at the PrestaShop codebase"
date:   2021-08-02
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
twitter_image: /assets/images/theme/banner-core-weekly.jpg
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 26th of July to Sunday 1st of August 2021.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)

## General messages

Dear developers,

Release patch 1.7.7.6 is [close to being delivered](https://github.com/PrestaShop/PrestaShop/issues/25202#issuecomment-889844880) while Release Candidate 1.7.8.0 is also [approaching the launchpad](https://github.com/PrestaShop/PrestaShop/issues/23010#issuecomment-890881293).

We are also preparing a new format for the incoming [Public OSS Demo](https://build.prestashop.com/news/upcoming-demo-7-2021/).

You might have noticed some heavy work being done [on the developer documentation](https://github.com/PrestaShop/docs/pull/1095). We will soon have [to maintain multiple versions of the documentation](https://github.com/PrestaShop/docs/issues/1090), this requires changes in how we build the site: the content will stay in the Docs repository, while the site itself has been moved to an [independent DevDocs site repository](https://github.com/PrestaShop/devdocs-site). Also, the [DevDocs' theme](https://github.com/PrestaShop/ps-docs-theme) has also been moved to an independent repository so it can be reused in the near future.


## Releases

* [Socialfollow](https://github.com/PrestaShop/ps_socialfollow) module: [v2.2.0](https://github.com/PrestaShop/ps_socialfollow/releases/tag/v2.2.0)
* [Linklist](https://github.com/PrestaShop/ps_linklist) module: [v5.0.4](https://github.com/PrestaShop/ps_linklist/releases/tag/v5.0.4)
* [Google Analytics](https://github.com/PrestaShop/ps_googleanalytics) module: [v4.1.0](https://github.com/PrestaShop/ps_googleanalytics/releases/tag/v4.1.0)


## A quick update about PrestaShop's GitHub issues and pull requests:

- [41 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2021-07-26..2021-08-01) have been created in the project repositories;
- [50 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2021-07-26..2021-08-01), including [14 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2021-07-26..2021-08-01) on the core;
- [39 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2021-07-26..2021-08-01) in the project repositories;
- [45 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2021-07-26..2021-08-01), including [41 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2021-07-26..2021-08-01).



## Code changes in the 'develop' branch


### Core
* [#25445](https://github.com/PrestaShop/PrestaShop/pull/25445): Fix wrong service for TranslationExtension. Thank you [@kpodemski](https://github.com/kpodemski)
* [#25435](https://github.com/PrestaShop/PrestaShop/pull/25435): Update twig to v3, by [@atomiix](https://github.com/atomiix)
* [#25413](https://github.com/PrestaShop/PrestaShop/pull/25413): Fix performance issue on Smarty template caching. Thank you [@lukaslau](https://github.com/lukaslau)


### Back office
* [#25439](https://github.com/PrestaShop/PrestaShop/pull/25439): BO - Customer View page - Added alert when removing a voucher, by [@Progi1984](https://github.com/Progi1984)
* [#25419](https://github.com/PrestaShop/PrestaShop/pull/25419): Introduce new product form structure for BO Experimental Product page, by [@jolelievre](https://github.com/jolelievre)
* [#25305](https://github.com/PrestaShop/PrestaShop/pull/25305): States : Added add button only on listing pages, by [@Progi1984](https://github.com/Progi1984)
* [#25301](https://github.com/PrestaShop/PrestaShop/pull/25301): Display validation when Enable/Disable webservice keys by bulk actions, by [@Progi1984](https://github.com/Progi1984)
* [#25186](https://github.com/PrestaShop/PrestaShop/pull/25186): Refacto stock page using TypeScript, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#25157](https://github.com/PrestaShop/PrestaShop/pull/25157): Improve admin product list header. Thank you [@Hlavtox](https://github.com/Hlavtox)
* [#25139](https://github.com/PrestaShop/PrestaShop/pull/25139): Fix the path of the "form_warehouse_combination". Thank you [@tups](https://github.com/tups)
* [#25056](https://github.com/PrestaShop/PrestaShop/pull/25056): Fix BO order create responsivity. Thank you [@Hlavtox](https://github.com/Hlavtox)
* [#24786](https://github.com/PrestaShop/PrestaShop/pull/24786): Remove unused backoffice footer, by [@Progi1984](https://github.com/Progi1984)


### Front office
* [#25433](https://github.com/PrestaShop/PrestaShop/pull/25433): Fix `ObjectModel::add()` force_id usage for multilang model. Thank you [@jf-viguier](https://github.com/jf-viguier)
* [#24684](https://github.com/PrestaShop/PrestaShop/pull/24684): Option to override CMS category template. Thank you [@kpodemski](https://github.com/kpodemski)


## Code changes in the '1.7.7.x' branch


### Core
* [#25449](https://github.com/PrestaShop/PrestaShop/pull/25449): Build assets on 1.7.7.x , by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#25447](https://github.com/PrestaShop/PrestaShop/pull/25447): Update prestashop modules on 1.7.7.x, by [@matthieu-rolland](https://github.com/matthieu-rolland)


### Back office
* [#25428](https://github.com/PrestaShop/PrestaShop/pull/25428): Don't recalculate total when PS_ORDER_RECALCULATE_SHIPPING is 0 and editing a carrier, by [@Progi1984](https://github.com/Progi1984)
* [#24991](https://github.com/PrestaShop/PrestaShop/pull/24991): Fix combination ecotax display and edition, by [@jolelievre](https://github.com/jolelievre)


## Code changes in modules, themes & tools


### Changes in developer documentation
* [#1096](https://github.com/PrestaShop/docs/pull/1096): Add a mention on underscore module name. Thank you [@jf-viguier](https://github.com/jf-viguier)
* [#1095](https://github.com/PrestaShop/docs/pull/1095): Prepare site for multiple versions, by [@eternoendless](https://github.com/eternoendless)
* [#1094](https://github.com/PrestaShop/docs/pull/1094): Bump php version php7.1-fpm ==> php 7.3-fpm. Thank you [@MaximeMichaud](https://github.com/MaximeMichaud)
* [#1093](https://github.com/PrestaShop/docs/pull/1093): Bump Prestashop version 1.7.3.2 ==> 1.7.7.5. Thank you [@MaximeMichaud](https://github.com/MaximeMichaud)


### Customer reassurance block module
* [#244](https://github.com/PrestaShop/blockreassurance/pull/244): Bump webpack from 5.46.0 to 5.47.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Faceted search module
* [#478](https://github.com/PrestaShop/ps_facetedsearch/pull/478): Bump webpack from 5.46.0 to 5.47.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Core Weekly Generator tool
* [#95](https://github.com/PrestaShop/core-weekly-generator/pull/95): Update configuration, by [@matks](https://github.com/matks)
* [#94](https://github.com/PrestaShop/core-weekly-generator/pull/94): Handle empty result, by [@matks](https://github.com/matks)
* [#93](https://github.com/PrestaShop/core-weekly-generator/pull/93): Fix README, by [@matks](https://github.com/matks)


### Developer documentation Hugo Theme
* [#1](https://github.com/PrestaShop/ps-docs-theme/pull/1): Add support for multiple versions, by [@eternoendless](https://github.com/eternoendless)


### Social Follow module
* [#28](https://github.com/PrestaShop/ps_socialfollow/pull/28): Release v2.2.0, by [@matks](https://github.com/matks)
* [#27](https://github.com/PrestaShop/ps_socialfollow/pull/27): Cleanup and bump to v2.2.0, by [@matks](https://github.com/matks)


### Links list module
* [#133](https://github.com/PrestaShop/ps_linklist/pull/133): Release v5.0.4, by [@atomiix](https://github.com/atomiix)
* [#132](https://github.com/PrestaShop/ps_linklist/pull/132): Bump to version 5.0.4, by [@atomiix](https://github.com/atomiix)


### OnBoarding module
* [#120](https://github.com/PrestaShop/welcome/pull/120): Remove code related to MBO, by [@PierreRambaud](https://github.com/PierreRambaud)


### MJML Theme Converter
* [#12](https://github.com/PrestaShop/mjml-theme-converter/pull/12): Add recycled packaging. Thank you [@okom3pom](https://github.com/okom3pom)
* [#7](https://github.com/PrestaShop/mjml-theme-converter/pull/7): Fix order customer comment and product out of stock, by [@jolelievre](https://github.com/jolelievre)


### Auto Upgrade module
* [#396](https://github.com/PrestaShop/autoupgrade/pull/396): Delete table before delete view, by [@atomiix](https://github.com/atomiix)
* [#395](https://github.com/PrestaShop/autoupgrade/pull/395): Move upgrade scripts from the Core to the autoupgrade module, by [@PierreRambaud](https://github.com/PierreRambaud)


### Example modules
* [#62](https://github.com/PrestaShop/example-modules/pull/62): Publish Demo SymfonyForm 1.1.0 : add other and choice form types to example form. Thank you [@JevgenijVisockij](https://github.com/JevgenijVisockij)
* [#58](https://github.com/PrestaShop/example-modules/pull/58): Publish Example module demonstrating Javascript router component usage. Thank you [@zuk3975](https://github.com/zuk3975)


### Google Analytics module
* [#92](https://github.com/PrestaShop/ps_googleanalytics/pull/92): Release v4.1.0, by [@matks](https://github.com/matks)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@jf-viguier](https://github.com/jf-viguier), [@Progi1984](https://github.com/Progi1984), [@matthieu-rolland](https://github.com/matthieu-rolland), [@kpodemski](https://github.com/kpodemski), [@dependabot[bot]](https://github.com/apps/dependabot), [@matks](https://github.com/matks), [@eternoendless](https://github.com/eternoendless), [@atomiix](https://github.com/atomiix), [@jolelievre](https://github.com/jolelievre), [@MaximeMichaud](https://github.com/MaximeMichaud), [@lukaslau](https://github.com/lukaslau), [@PierreRambaud](https://github.com/PierreRambaud), [@okom3pom](https://github.com/okom3pom), [@NeOMakinG](https://github.com/NeOMakinG), [@Hlavtox](https://github.com/Hlavtox), [@tups](https://github.com/tups), [@JevgenijVisockij](https://github.com/JevgenijVisockij), [@zuk3975](https://github.com/zuk3975)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

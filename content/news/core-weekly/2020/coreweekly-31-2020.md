---
layout: post
aliases: ["/news/coreweekly-31-2020"]
title:  "PrestaShop Core Weekly - Week 31 of 2020"
subtitle: "An inside look at the PrestaShop codebase"
date:   2020-08-03
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
twitter_image: /assets/images/theme/banner-core-weekly.jpg
icon: icon-calendar
tags:
 - core-monthly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 27th of July to Sunday 2th of August 2020.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)

## Releases

* [Ps_googleanalytics](https://github.com/PrestaShop/ps_googleanalytics): [v4.0.0](https://github.com/PrestaShop/ps_googleanalytics/releases/tag/v4.0.0)


## A quick update about PrestaShop's GitHub issues and pull requests:

- [48 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2020-07-27..2020-08-02) have been created in the project repositories;
- [61 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2020-07-27..2020-08-02), including [15 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2020-07-27..2020-08-02) on the core;
- [52 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2020-07-27..2020-08-02) in the project repositories;
- [57 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2020-07-27..2020-08-02), including [53 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2020-07-27..2020-08-02).



## Code changes in the 'develop' branch


### Core
* [#20363](https://github.com/PrestaShop/PrestaShop/pull/20363): Fixed duplication of Currencies after install/remove, by [@Progi1984](https://github.com/Progi1984)


### Back office
* [#20364](https://github.com/PrestaShop/PrestaShop/pull/20364): Fix typo. Thank you [@ksaandev](https://github.com/ksaandev)
* [#20361](https://github.com/PrestaShop/PrestaShop/pull/20361): Add Apple Touch Icon, by [@Progi1984](https://github.com/Progi1984)
* [#20329](https://github.com/PrestaShop/PrestaShop/pull/20329): Format add webservice key log like deletion log. Thank you [@ksaandev](https://github.com/ksaandev)
* [#20328](https://github.com/PrestaShop/PrestaShop/pull/20328): Fixed the title 'List of products without description', by [@Progi1984](https://github.com/Progi1984)
* [#20207](https://github.com/PrestaShop/PrestaShop/pull/20207):  Added hook & gravatar management for avatar employee , by [@Progi1984](https://github.com/Progi1984)
* [#20107](https://github.com/PrestaShop/PrestaShop/pull/20107): Add UpdateProductShipping command. Thank you [@zuk3975](https://github.com/zuk3975)
* [#17215](https://github.com/PrestaShop/PrestaShop/pull/17215): Symfony migration of Order statuses + Order return statuses listing and forms, by [@sowbiba](https://github.com/sowbiba)


### Front office
* [#20282](https://github.com/PrestaShop/PrestaShop/pull/20282): Reduce conditions complexity. Thank you [@davidglezz](https://github.com/davidglezz)
* [#19965](https://github.com/PrestaShop/PrestaShop/pull/19965): Add High DPI support to ImageRetriever. Thank you [@daresh](https://github.com/daresh)


### Installer
* [#19856](https://github.com/PrestaShop/PrestaShop/pull/19856): Check Select Privilege in the Install Process, by [@Progi1984](https://github.com/Progi1984)


### Tests
* [#20407](https://github.com/PrestaShop/PrestaShop/pull/20407): Use sharedStorage for exceptions in behat domain contexts. Thank you [@zuk3975](https://github.com/zuk3975)
* [#20386](https://github.com/PrestaShop/PrestaShop/pull/20386): Add tests for Tools rounding functions, by [@matks](https://github.com/matks)
* [#20362](https://github.com/PrestaShop/PrestaShop/pull/20362): Functional tests -  Fix nightly fails after merging 1.7.7.x into develop, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#20358](https://github.com/PrestaShop/PrestaShop/pull/20358): Improve UI tests readme, by [@matks](https://github.com/matks)
* [#20356](https://github.com/PrestaShop/PrestaShop/pull/20356): Fix phpstan ignore lines, by [@matks](https://github.com/matks)


### Merge
* [#20304](https://github.com/PrestaShop/PrestaShop/pull/20304): Merge branch "1.7.7.x" into "develop", by [@boubkerbribri](https://github.com/boubkerbribri)


## Code changes in the '1.7.7.x' branch


### Core
* [#20398](https://github.com/PrestaShop/PrestaShop/pull/20398): Fixed Cache Problem in Language & Currency, by [@Progi1984](https://github.com/Progi1984)
* [#20324](https://github.com/PrestaShop/PrestaShop/pull/20324): Set editorconfig to indent yml files using 4 spaces instead of two, by [@eternoendless](https://github.com/eternoendless)
* [#20137](https://github.com/PrestaShop/PrestaShop/pull/20137): Computing precision: set minimum computing precision value to zero, by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#15049](https://github.com/PrestaShop/PrestaShop/pull/15049): Fix wrong hook names, by [@eternoendless](https://github.com/eternoendless)


### Back office
* [#20319](https://github.com/PrestaShop/PrestaShop/pull/20319): Cannot remove attributes if token is disabled, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#20311](https://github.com/PrestaShop/PrestaShop/pull/20311): Mark deprecated order hooks for 1.7.7 as such, by [@matks](https://github.com/matks)
* [#20303](https://github.com/PrestaShop/PrestaShop/pull/20303): Fix bad redirection after error in address controller - edit usecase, by [@matks](https://github.com/matks)
* [#20284](https://github.com/PrestaShop/PrestaShop/pull/20284): Order address country, by [@jolelievre](https://github.com/jolelievre)
* [#20198](https://github.com/PrestaShop/PrestaShop/pull/20198): Product supplier_reference is not updated when saving a product in the BO, by [@PierreRambaud](https://github.com/PierreRambaud)


### Tests
* [#20368](https://github.com/PrestaShop/PrestaShop/pull/20368): Functional tests - Add browser listeners to tests, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#20360](https://github.com/PrestaShop/PrestaShop/pull/20360): Functional tests - Reset orders before going to order view page, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#20318](https://github.com/PrestaShop/PrestaShop/pull/20318): Functional tests - Add new test 'View guest from orders page', by [@boubkerbribri](https://github.com/boubkerbribri)


## Code changes in modules, themes & tools


### Core Weekly Generator tool
* [#43](https://github.com/PrestaShop/core-weekly-generator/pull/43): Bump elliptic from 6.5.1 to 6.5.3. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#42](https://github.com/PrestaShop/core-weekly-generator/pull/42): Mention cache, by [@matks](https://github.com/matks)
* [#40](https://github.com/PrestaShop/core-weekly-generator/pull/40): Generate a few more items automatically, by [@matks](https://github.com/matks)


### PHP Developer Tools
* [#34](https://github.com/PrestaShop/php-dev-tools/pull/34): Use bootstrapFiles in phpstan config, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### example_module_mailtheme
* [#9](https://github.com/PrestaShop/example_module_mailtheme/pull/9): Bump elliptic from 6.5.0 to 6.5.3. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### Changes in developer documentation
* [#649](https://github.com/PrestaShop/docs/pull/649): Explain security policy and security process, by [@matks](https://github.com/matks)
* [#648](https://github.com/PrestaShop/docs/pull/648): Highlight min version for modern controllers, by [@matks](https://github.com/matks)
* [#646](https://github.com/PrestaShop/docs/pull/646): Bump elliptic from 6.5.2 to 6.5.3 in /src/themes/hugo-theme-learn/_src. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#645](https://github.com/PrestaShop/docs/pull/645): It's Modules, not Module. Thank you [@elboletaire](https://github.com/elboletaire)
* [#627](https://github.com/PrestaShop/docs/pull/627): Update architecture documentation, by [@eternoendless](https://github.com/eternoendless)
* [#619](https://github.com/PrestaShop/docs/pull/619): Add BC breaks information for dashboard modules and other notable changes for 1.7.6.6, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#613](https://github.com/PrestaShop/docs/pull/613): Add the overriding selectors page, by [@NeOMakinG](https://github.com/NeOMakinG)


### Faceted search module
* [#188](https://github.com/PrestaShop/ps_facetedsearch/pull/188): Bump elliptic from 6.4.1 to 6.5.3. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### Shopping cart module
* [#65](https://github.com/PrestaShop/ps_shoppingcart/pull/65): Improve modal description in JS, by [@matks](https://github.com/matks)


### Link list
* [#102](https://github.com/PrestaShop/ps_linklist/pull/102): Change private to protected, by [@PierreRambaud](https://github.com/PierreRambaud)


### Wishlist block
* [#75](https://github.com/PrestaShop/blockwishlist/pull/75): Add placeholder instead of multiple i18n strings, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#74](https://github.com/PrestaShop/blockwishlist/pull/74): Create database tables during upgrade from PS 1.6, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#73](https://github.com/PrestaShop/blockwishlist/pull/73): Fix refresh cache and clean up some folders. Thank you [@zalexki](https://github.com/zalexki)
* [#72](https://github.com/PrestaShop/blockwishlist/pull/72): fix default wishlist listing. Thank you [@PoulainMaxime](https://github.com/PoulainMaxime)
* [#71](https://github.com/PrestaShop/blockwishlist/pull/71): Replace calls to l() with trans(), by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#69](https://github.com/PrestaShop/blockwishlist/pull/69): Make module prop public, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Google Analytics module
* [#55](https://github.com/PrestaShop/ps_googleanalytics/pull/55): Prepare Release v4.0.0, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Banner
* [#20](https://github.com/PrestaShop/ps_banner/pull/20): Add dependabot config file, by [@PierreRambaud](https://github.com/PierreRambaud)


### PrestonBot
* [#94](https://github.com/PrestaShop/prestonbot/pull/94): Make relatedTicket mandatory in the PR's description, by [@atomiix](https://github.com/atomiix)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@dependabot[bot]](https://github.com/apps/dependabot), [@Quetzacoalt91](https://github.com/Quetzacoalt91), [@zuk3975](https://github.com/zuk3975), [@matks](https://github.com/matks), [@Progi1984](https://github.com/Progi1984), [@PierreRambaud](https://github.com/PierreRambaud), [@boubkerbribri](https://github.com/boubkerbribri), [@NeOMakinG](https://github.com/NeOMakinG), [@ksaandev](https://github.com/ksaandev), [@elboletaire](https://github.com/elboletaire), [@zalexki](https://github.com/zalexki), [@PoulainMaxime](https://github.com/PoulainMaxime), [@eternoendless](https://github.com/eternoendless), [@jolelievre](https://github.com/jolelievre), [@davidglezz](https://github.com/davidglezz), [@matthieu-rolland](https://github.com/matthieu-rolland), [@atomiix](https://github.com/atomiix), [@daresh](https://github.com/daresh), [@sowbiba](https://github.com/sowbiba)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!


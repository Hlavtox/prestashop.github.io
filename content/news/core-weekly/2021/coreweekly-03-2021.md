---
layout: post
aliases: ["/news/coreweekly-03-2021"]
title:  "PrestaShop Core Weekly - Week 3 of 2021"
subtitle: "An inside look at the PrestaShop codebase"
date:   2021-01-25
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
twitter_image: /assets/images/theme/banner-core-weekly.jpg
icon: icon-calendar
tags:
 - core-monthly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 18th to Sunday 24th of January 2021.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)


## Releases

* [php-dev-tools](https://github.com/PrestaShop/php-dev-tools): [v3.14](https://github.com/PrestaShop/php-dev-tools/releases/tag/v3.14)


## A quick update about PrestaShop's GitHub issues and pull requests:

- [67 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2021-01-18..2021-01-24) have been created in the project repositories;
- [46 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2021-01-18..2021-01-24), including [9 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2021-01-18..2021-01-24) on the core;
- [118 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2021-01-18..2021-01-24) in the project repositories;
- [98 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2021-01-18..2021-01-24), including [71 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2021-01-18..2021-01-24).



## Code changes in the 'develop' branch


### Core
* [#22887](https://github.com/PrestaShop/PrestaShop/pull/22887): Improve TypedRegexValidator->getPattern(). Thank you [@davidglezz](https://github.com/davidglezz)
* [#22861](https://github.com/PrestaShop/PrestaShop/pull/22861): Updated JS Routing file. Thank you [@github-actions[bot]](https://github.com/apps/github-actions)
* [#20446](https://github.com/PrestaShop/PrestaShop/pull/20446): Fix cache class. Thank you [@davidglezz](https://github.com/davidglezz)


### Back office
* [#22922](https://github.com/PrestaShop/PrestaShop/pull/22922): New hooks on grid component table. Thank you [@kpodemski](https://github.com/kpodemski)
* [#22895](https://github.com/PrestaShop/PrestaShop/pull/22895): Adjust items alignment of order view header, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#22884](https://github.com/PrestaShop/PrestaShop/pull/22884): Fix carrier depth, height and width limits. Thank you [@Prestaworks](https://github.com/Prestaworks)
* [#18136](https://github.com/PrestaShop/PrestaShop/pull/18136): Use grid common search action where possible (1.7.8 target). Thank you [@zuk3975](https://github.com/zuk3975)


### Front office
* [#19231](https://github.com/PrestaShop/PrestaShop/pull/19231): Add caching on Theme Yaml parsing. Thank you [@Kioob](https://github.com/Kioob)


### Installer
* [#22944](https://github.com/PrestaShop/PrestaShop/pull/22944): Fix undefined index when iso doesn't exists in language list, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#19818](https://github.com/PrestaShop/PrestaShop/pull/19818): Added Countries Translations (Installation & LocalizationPack), by [@Progi1984](https://github.com/Progi1984)


### Tests
* [#22935](https://github.com/PrestaShop/PrestaShop/pull/22935): Update GitHub Action actions/checkout to v2, by [@matks](https://github.com/matks)
* [#22890](https://github.com/PrestaShop/PrestaShop/pull/22890): Fix shopping cart tests for the nightly, by [@boubkerbribri](https://github.com/boubkerbribri)


## Code changes in the '1.7.7.x' branch


### Core
* [#22841](https://github.com/PrestaShop/PrestaShop/pull/22841): Bring back vat number to address on order view. Thank you [@kpodemski](https://github.com/kpodemski)


### Back office
* [#22909](https://github.com/PrestaShop/PrestaShop/pull/22909): BO - Create Order - Updated product list when adresses changed, by [@Progi1984](https://github.com/Progi1984)
* [#22863](https://github.com/PrestaShop/PrestaShop/pull/22863): Fix reference in Shopping carts view. Thank you [@kpodemski](https://github.com/kpodemski)
* [#22805](https://github.com/PrestaShop/PrestaShop/pull/22805): BO - Orders page - Cannot delete a product restricted by a cart rule, by [@Progi1984](https://github.com/Progi1984)


### Tests
* [#22927](https://github.com/PrestaShop/PrestaShop/pull/22927): Fix nightly 21-01-2021 on 1.7.7.x, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#22912](https://github.com/PrestaShop/PrestaShop/pull/22912): Fix nightly tests failing on 20-01-2021, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#22900](https://github.com/PrestaShop/PrestaShop/pull/22900): Add test 'Test handling charges for carriers in FO'. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#22879](https://github.com/PrestaShop/PrestaShop/pull/22879): Add test 'CRUD shop group'. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#22876](https://github.com/PrestaShop/PrestaShop/pull/22876): Add test 'Filter,sort and pagination logs'. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#22874](https://github.com/PrestaShop/PrestaShop/pull/22874): Add test 'Check number of orders in order history page', by [@boubkerbribri](https://github.com/boubkerbribri)
* [#22856](https://github.com/PrestaShop/PrestaShop/pull/22856): Add test 'Check customer block' in order page. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#22855](https://github.com/PrestaShop/PrestaShop/pull/22855): Add test 'View vouchers on FO account Page', by [@boubkerbribri](https://github.com/boubkerbribri)
* [#22762](https://github.com/PrestaShop/PrestaShop/pull/22762): Add test 'Filter sort pagination shop groups'. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)


## Code changes in modules, themes & tools


### Customer reassurance block module
* [#112](https://github.com/PrestaShop/blockreassurance/pull/112): Bump friendsofphp/php-cs-fixer from 2.18.0 to 2.18.1. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#111](https://github.com/PrestaShop/blockreassurance/pull/111): Bump webpack-cli from 4.3.1 to 4.4.0. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#110](https://github.com/PrestaShop/blockreassurance/pull/110): Bump webpack from 5.15.0 to 5.16.0. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#109](https://github.com/PrestaShop/blockreassurance/pull/109): Bump webpack from 5.14.0 to 5.15.0. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#108](https://github.com/PrestaShop/blockreassurance/pull/108): Bump friendsofphp/php-cs-fixer from 2.17.3 to 2.18.0. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### PHP Developer Tools
* [#49](https://github.com/PrestaShop/php-dev-tools/pull/49): Update PHP Syntax linter github action to use standard GA instead of prestashop/github-action-php-lint@master, by [@matks](https://github.com/matks)
* [#48](https://github.com/PrestaShop/php-dev-tools/pull/48): Update PHP CS Fixer github action to use standard GA instead of prestashopcorp/github-action-php-cs-fixer, by [@matks](https://github.com/matks)
* [#46](https://github.com/PrestaShop/php-dev-tools/pull/46): Add stub for Module::getInstanceByName always returning true, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### QA nightly results
* [#53](https://github.com/PrestaShop/QANightlyResults/pull/53): Merge develop into master, by [@atomiix](https://github.com/atomiix)
* [#52](https://github.com/PrestaShop/QANightlyResults/pull/52): Upgrade composer dependencies, by [@atomiix](https://github.com/atomiix)


### Nightly board
* [#53](https://github.com/PrestaShop/nightly-board/pull/53): Merge develop into master, by [@atomiix](https://github.com/atomiix)
* [#52](https://github.com/PrestaShop/nightly-board/pull/52): Handle autoupgrade campagne, by [@atomiix](https://github.com/atomiix)


### Changes in developer documentation
* [#848](https://github.com/PrestaShop/docs/pull/848): New grid hooks from 1.7.8. Thank you [@kpodemski](https://github.com/kpodemski)
* [#847](https://github.com/PrestaShop/docs/pull/847): Added displayOrderPreview to the hook list. Thank you [@dpatou](https://github.com/dpatou)


### User documentation landing page
* [#19](https://github.com/PrestaShop/user-documentation-landing/pull/19): chore(deps-dev): bump sass from 1.32.4 to 1.32.5. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#18](https://github.com/PrestaShop/user-documentation-landing/pull/18): fix(deps): bump core-js from 3.8.2 to 3.8.3. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#16](https://github.com/PrestaShop/user-documentation-landing/pull/16): chore(deps-dev): bump eslint from 7.17.0 to 7.18.0. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### Faceted search module
* [#309](https://github.com/PrestaShop/ps_facetedsearch/pull/309): Bump webpack from 5.15.0 to 5.16.0. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#308](https://github.com/PrestaShop/ps_facetedsearch/pull/308): Bump prestashop/php-dev-tools from 3.13 to 3.14. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#307](https://github.com/PrestaShop/ps_facetedsearch/pull/307): Bump webpack from 5.14.0 to 5.15.0. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### PrestaShop Specifications
* [#201](https://github.com/PrestaShop/prestashop-specs/pull/201): Update advanced_parameters-webservice.md. Thank you [@justeen35](https://github.com/justeen35)
* [#200](https://github.com/PrestaShop/prestashop-specs/pull/200): Specify empty search results behaviors, by [@LouiseBonnard](https://github.com/LouiseBonnard)
* [#199](https://github.com/PrestaShop/prestashop-specs/pull/199): Add translation workflow, by [@LouiseBonnard](https://github.com/LouiseBonnard)
* [#193](https://github.com/PrestaShop/prestashop-specs/pull/193): Add multistore behavior for catalog price rule, by [@marionf](https://github.com/marionf)
* [#191](https://github.com/PrestaShop/prestashop-specs/pull/191): Add missing specs for sql manager page, by [@marionf](https://github.com/marionf)
* [#167](https://github.com/PrestaShop/prestashop-specs/pull/167): Update Order Page View.md. Thank you [@MatShir](https://github.com/MatShir)


### Example modules
* [#37](https://github.com/PrestaShop/example-modules/pull/37): Homogenize composer.json authors, by [@matks](https://github.com/matks)
* [#36](https://github.com/PrestaShop/example-modules/pull/36): Add logos for all modules, by [@matks](https://github.com/matks)
* [#33](https://github.com/PrestaShop/example-modules/pull/33): Copy demoextendsymfonyform1 into demoextendsymfonyform3, by [@matks](https://github.com/matks)
* [#31](https://github.com/PrestaShop/example-modules/pull/31): Demonstrate displayOrderPreview. Thank you [@kpodemski](https://github.com/kpodemski)


### Category tree links module
* [#43](https://github.com/PrestaShop/ps_categorytree/pull/43): Bump prestashop/php-dev-tools from 3.9 to 3.14. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### Search Bar module
* [#28](https://github.com/PrestaShop/ps_searchbar/pull/28): Bump prestashop/php-dev-tools from 3.13 to 3.14. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### Shopping cart module
* [#75](https://github.com/PrestaShop/ps_shoppingcart/pull/75): Bump prestashop/php-dev-tools from 3.9 to 3.14. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### Simple HTML table display module
* [#20](https://github.com/PrestaShop/gridhtml/pull/20): Bump prestashop/php-dev-tools from 3.13 to 3.14. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### Dashboard Trends module
* [#42](https://github.com/PrestaShop/dashtrends/pull/42): Bump prestashop/php-dev-tools from 3.13 to 3.14. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### Customer "Sign in" link module
* [#31](https://github.com/PrestaShop/ps_customersignin/pull/31): Bump prestashop/php-dev-tools from 3.13 to 3.14. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### OnBoarding module
* [#99](https://github.com/PrestaShop/welcome/pull/99): Bump prestashop/php-dev-tools from 3.13 to 3.14. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### Check payment module
* [#46](https://github.com/PrestaShop/ps_checkpayment/pull/46): Bump prestashop/php-dev-tools from 3.13 to 3.14. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### Custom text module
* [#54](https://github.com/PrestaShop/ps_customtext/pull/54): Bump prestashop/php-dev-tools from 3.13 to 3.14. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### Product Comments module
* [#97](https://github.com/PrestaShop/productcomments/pull/97): Bump prestashop/php-dev-tools from 3.13 to 3.14. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### Theme customization module
* [#41](https://github.com/PrestaShop/ps_themecusto/pull/41): Bump prestashop/php-dev-tools from 3.13 to 3.14. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### Order Notifications on the Favicon module
* [#27](https://github.com/PrestaShop/ps_faviconnotificationbo/pull/27): Bump prestashop/php-dev-tools from 3.13 to 3.14. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### PrestaShop PHPStan extension
* [#4](https://github.com/PrestaShop/phpstan-prestashop/pull/4): Add badges in README, by [@matks](https://github.com/matks)


### Links list module
* [#109](https://github.com/PrestaShop/ps_linklist/pull/109): Fix block name validation. Thank you [@kpodemski](https://github.com/kpodemski)


### MJML Theme Converter
* [#10](https://github.com/PrestaShop/mjml-theme-converter/pull/10): Update dependencies to be compatible with PHP 7.3, by [@jolelievre](https://github.com/jolelievre)


### Product details statistics module
* [#18](https://github.com/PrestaShop/statsproduct/pull/18): Fix graphic stats stop working since PHP 7.1 version. Thank you [@PrestanceDesign](https://github.com/PrestanceDesign)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@PierreRambaud](https://github.com/PierreRambaud), [@dependabot[bot]](https://github.com/apps/dependabot), [@matks](https://github.com/matks), [@atomiix](https://github.com/atomiix), [@boubkerbribri](https://github.com/boubkerbribri), [@kpodemski](https://github.com/kpodemski), [@Progi1984](https://github.com/Progi1984), [@nesrineabdmouleh](https://github.com/nesrineabdmouleh), [@justeen35](https://github.com/justeen35), [@NeOMakinG](https://github.com/NeOMakinG), [@davidglezz](https://github.com/davidglezz), [@Prestaworks](https://github.com/Prestaworks), [@Quetzacoalt91](https://github.com/Quetzacoalt91), [@github-actions[bot]](https://github.com/apps/github-actions), [@dpatou](https://github.com/dpatou), [@LouiseBonnard](https://github.com/LouiseBonnard), [@marionf](https://github.com/marionf), [@jolelievre](https://github.com/jolelievre), [@MatShir](https://github.com/MatShir), [@PrestanceDesign](https://github.com/PrestanceDesign), [@Kioob](https://github.com/Kioob), [@zuk3975](https://github.com/zuk3975)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

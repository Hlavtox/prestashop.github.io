---
layout: post
aliases: ["/news/coreweekly-week-45-2019"]
title:  "PrestaShop Core Weekly - Week 45 of 2019"
subtitle: "An inside look at the PrestaShop codebase"
date:   2019-11-20 10:00:00
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 04th to Sunday 10th of November 2019.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)


## A quick update about PrestaShop's GitHub issues and pull requests:

- [61 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2019-11-04..2019-11-10) have been created in the project repositories;
- [60 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2019-11-04..2019-11-10), including [18 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2019-11-04..2019-11-10) on the core;
- [100 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2019-11-04..2019-11-10) in the project repositories;
- [88 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2019-11-04..2019-11-10), including [83 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2019-11-04..2019-11-10).
        


## Code changes in the 'develop' branch


### Core
* [#16241](https://github.com/PrestaShop/PrestaShop/pull/16241): Improve install doc, by [@matks](https://github.com/matks)
* [#16237](https://github.com/PrestaShop/PrestaShop/pull/16237): Set Demo mode only if undefined, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#16176](https://github.com/PrestaShop/PrestaShop/pull/16176): Increase maximum hook length to 191 characters, by [@eternoendless](https://github.com/eternoendless)
* [#15022](https://github.com/PrestaShop/PrestaShop/pull/15022): Migration of Sell > Customer Service > Merchandise Returns page. Thank you [@rokaszygmantas](https://github.com/rokaszygmantas)


### Back office
* [#16319](https://github.com/PrestaShop/PrestaShop/pull/16319): Use customer group price display preference for display order in BO, by [@matks](https://github.com/matks)
* [#16312](https://github.com/PrestaShop/PrestaShop/pull/16312): Incorrect display value in Price Tab of admin product controller. Thank you [@WebXYAgency](https://github.com/WebXYAgency)
* [#16304](https://github.com/PrestaShop/PrestaShop/pull/16304): change wording of lifetime of BO cookies help label. Thank you [@atomiix](https://github.com/atomiix)
* [#16285](https://github.com/PrestaShop/PrestaShop/pull/16285): Fix ajax spinner not disappearing after Ajax is done, by [@eternoendless](https://github.com/eternoendless)
* [#16281](https://github.com/PrestaShop/PrestaShop/pull/16281): Update wording and add a link in product options tab, by [@marionf](https://github.com/marionf)
* [#16278](https://github.com/PrestaShop/PrestaShop/pull/16278): Use https links to doc instead of http, by [@matks](https://github.com/matks)
* [#16271](https://github.com/PrestaShop/PrestaShop/pull/16271): Remove useless checkbox in product options tab for attached files, by [@marionf](https://github.com/marionf)
* [#16266](https://github.com/PrestaShop/PrestaShop/pull/16266): Fix ajax exception when search for a product in order creation page, by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#16244](https://github.com/PrestaShop/PrestaShop/pull/16244): Update Costa Rican, Peruvian and Brazilian tax rates, by [@LouiseBonnard](https://github.com/LouiseBonnard)
* [#16225](https://github.com/PrestaShop/PrestaShop/pull/16225): Fix prices display in new order page. Thank you [@sarjon](https://github.com/sarjon)
* [#16209](https://github.com/PrestaShop/PrestaShop/pull/16209): Use local fonts in BO default theme, by [@eternoendless](https://github.com/eternoendless)
* [#16159](https://github.com/PrestaShop/PrestaShop/pull/16159): Fix category checkbox redirect. Thank you [@atomiix](https://github.com/atomiix)
* [#16084](https://github.com/PrestaShop/PrestaShop/pull/16084): Migrates Merchandise returns for Orders view. Thank you [@sarjon](https://github.com/sarjon)
* [#16079](https://github.com/PrestaShop/PrestaShop/pull/16079): Update Azerbaijani tax rates, by [@LouiseBonnard](https://github.com/LouiseBonnard)
* [#16078](https://github.com/PrestaShop/PrestaShop/pull/16078): Update Argentinian conversion and tax rates, by [@LouiseBonnard](https://github.com/LouiseBonnard)
* [#16065](https://github.com/PrestaShop/PrestaShop/pull/16065): Migrates Shipping block of new Order View page. Thank you [@sarjon](https://github.com/sarjon)
* [#16046](https://github.com/PrestaShop/PrestaShop/pull/16046): Migrate Documents block of Order View page. Thank you [@sarjon](https://github.com/sarjon)
* [#16033](https://github.com/PrestaShop/PrestaShop/pull/16033): Introduces kpi design update for orders listing page - also includes layout changes for all kpi's in migrated pages. Thank you [@tomas862](https://github.com/tomas862)


### Front office
* [#16235](https://github.com/PrestaShop/PrestaShop/pull/16235): Correct vouchers reductions display values in cart summary, by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#16180](https://github.com/PrestaShop/PrestaShop/pull/16180): Use Media Server for assets (CSS, JS, Images), by [@Progi1984](https://github.com/Progi1984)
* [#16147](https://github.com/PrestaShop/PrestaShop/pull/16147): Add CSS sizes for images in custom text block. Thank you [@Klemart3D](https://github.com/Klemart3D)
* [#16099](https://github.com/PrestaShop/PrestaShop/pull/16099): Makes checkout js code easier to understand. Thank you [@atomiix](https://github.com/atomiix)
* [#16069](https://github.com/PrestaShop/PrestaShop/pull/16069): Change wording in FO when there is specific price by quantity. Thank you [@atomiix](https://github.com/atomiix)
* [#16063](https://github.com/PrestaShop/PrestaShop/pull/16063): Improve wording on order confirmation email. Thank you [@atomiix](https://github.com/atomiix)


### Installer
* [#16305](https://github.com/PrestaShop/PrestaShop/pull/16305): Fix SQL upgrade for 1.7.7.0 (missing FROM), by [@matks](https://github.com/matks)


### Tests
* [#16309](https://github.com/PrestaShop/PrestaShop/pull/16309): Tests - Separate BO pages, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#16297](https://github.com/PrestaShop/PrestaShop/pull/16297): Functional tests - Using the correct element in loop for brands tests , by [@boubkerbribri](https://github.com/boubkerbribri)
* [#16296](https://github.com/PrestaShop/PrestaShop/pull/16296): Functional Tests - Add BO tests for Supplier, by [@boubkerbribri](https://github.com/boubkerbribri)


## Code changes in the '1.7.6.x' branch


### Core
* [#16258](https://github.com/PrestaShop/PrestaShop/pull/16258): Remove unnecessary require_once config.inc, by [@matks](https://github.com/matks)


### Back office
* [#16265](https://github.com/PrestaShop/PrestaShop/pull/16265): Fix category checkbox redirect (Backport #16159). Thank you [@atomiix](https://github.com/atomiix)


### Front office
* [#16274](https://github.com/PrestaShop/PrestaShop/pull/16274): Fix contact us email display. Thank you [@atomiix](https://github.com/atomiix)


## Code changes in modules, themes & tools


### carriercompare
* [#11](https://github.com/PrestaShop/carriercompare/pull/11): Add notice about end of life and link to the new module, by [@PierreRambaud](https://github.com/PierreRambaud)


### producttooltip
* [#8](https://github.com/PrestaShop/producttooltip/pull/8): Add notice about end of life and link to the new module, by [@PierreRambaud](https://github.com/PierreRambaud)


### productscategory
* [#8](https://github.com/PrestaShop/productscategory/pull/8): Add notice about end of life and link to the new module, by [@PierreRambaud](https://github.com/PierreRambaud)


### crossselling
* [#18](https://github.com/PrestaShop/crossselling/pull/18): Add notice about end of life and link to the new module, by [@PierreRambaud](https://github.com/PierreRambaud)


### blockviewed
* [#1](https://github.com/PrestaShop/blockviewed/pull/1): Add notice about end of life and link to the new module, by [@PierreRambaud](https://github.com/PierreRambaud)


### blockrss
* [#4](https://github.com/PrestaShop/blockrss/pull/4): Add notice about end of life and link to the new module, by [@PierreRambaud](https://github.com/PierreRambaud)


### blockspecials
* [#9](https://github.com/PrestaShop/blockspecials/pull/9): Add notice about end of life and link to the new module, by [@PierreRambaud](https://github.com/PierreRambaud)


### blocksupplier
* [#2](https://github.com/PrestaShop/blocksupplier/pull/2): Add notice about end of life and link to the new module, by [@PierreRambaud](https://github.com/PierreRambaud)


### blockmanufacturer
* [#4](https://github.com/PrestaShop/blockmanufacturer/pull/4): Add notice about end of life and link to the new module, by [@PierreRambaud](https://github.com/PierreRambaud)


### blockcustomerprivacy
* [#6](https://github.com/PrestaShop/blockcustomerprivacy/pull/6): Add notice about end of life and link to the new module, by [@PierreRambaud](https://github.com/PierreRambaud)


### onboarding
* [#9](https://github.com/PrestaShop/onboarding/pull/9): Add notice about end of life and link to the new module, by [@PierreRambaud](https://github.com/PierreRambaud)


### advancedeucompliance
* [#57](https://github.com/PrestaShop/advancedeucompliance/pull/57): Add notice about end of life and link to the new module, by [@PierreRambaud](https://github.com/PierreRambaud)


### mailalerts
* [#40](https://github.com/PrestaShop/mailalerts/pull/40): Add notice about end of life and link to the new module, by [@PierreRambaud](https://github.com/PierreRambaud)


### ganalytics
* [#119](https://github.com/PrestaShop/ganalytics/pull/119): Add notice about end of life and link to the new module, by [@PierreRambaud](https://github.com/PierreRambaud)


### blocknewsletter
* [#31](https://github.com/PrestaShop/blocknewsletter/pull/31): Add notice about end of life and link to the new module, by [@PierreRambaud](https://github.com/PierreRambaud)


### blockcmsinfo
* [#9](https://github.com/PrestaShop/blockcmsinfo/pull/9): Add notice about end of life and link to the new module, by [@PierreRambaud](https://github.com/PierreRambaud)


### homeslider
* [#20](https://github.com/PrestaShop/homeslider/pull/20): Add notice about end of life and link to the new module, by [@PierreRambaud](https://github.com/PierreRambaud)


### followup
* [#16](https://github.com/PrestaShop/followup/pull/16): Add notice about end of life and link to the new module, by [@PierreRambaud](https://github.com/PierreRambaud)


### blocktopmenu
* [#54](https://github.com/PrestaShop/blocktopmenu/pull/54): Add notice about end of life and link to the new module, by [@PierreRambaud](https://github.com/PierreRambaud)


### blockcms
* [#22](https://github.com/PrestaShop/blockcms/pull/22): Add notice about end of life and link to the new module, by [@PierreRambaud](https://github.com/PierreRambaud)


### socialsharing
* [#30](https://github.com/PrestaShop/socialsharing/pull/30): Add notice about end of life and link to the new module, by [@PierreRambaud](https://github.com/PierreRambaud)


### homefeatured
* [#14](https://github.com/PrestaShop/homefeatured/pull/14): Add notice about end of life and link to the new module, by [@PierreRambaud](https://github.com/PierreRambaud)


### cheque
* [#12](https://github.com/PrestaShop/cheque/pull/12): Add notice about end of life and link to the new module, by [@PierreRambaud](https://github.com/PierreRambaud)


### blockcategories
* [#20](https://github.com/PrestaShop/blockcategories/pull/20): Add notice about end of life and link to the new module, by [@PierreRambaud](https://github.com/PierreRambaud)


### blockbanner
* [#8](https://github.com/PrestaShop/blockbanner/pull/8): Add notice about end of life and link to the new module, by [@PierreRambaud](https://github.com/PierreRambaud)


### bankwire
* [#25](https://github.com/PrestaShop/bankwire/pull/25): Add notice about end of life and link to the new module, by [@PierreRambaud](https://github.com/PierreRambaud)


### feeder
* [#6](https://github.com/PrestaShop/feeder/pull/6): Add notice about end of life and link to the new module, by [@PierreRambaud](https://github.com/PierreRambaud)


### cashondelivery
* [#10](https://github.com/PrestaShop/cashondelivery/pull/10): Add notice about end of life and link to the new module, by [@PierreRambaud](https://github.com/PierreRambaud)


### blockuserinfo
* [#5](https://github.com/PrestaShop/blockuserinfo/pull/5): Add notice about end of life and link to the new module, by [@PierreRambaud](https://github.com/PierreRambaud)


### blocksearch
* [#8](https://github.com/PrestaShop/blocksearch/pull/8): Add notice about end of life and link to the new module, by [@PierreRambaud](https://github.com/PierreRambaud)


### blockcurrencies
* [#6](https://github.com/PrestaShop/blockcurrencies/pull/6): Add notice about end of life and link to the new module, by [@PierreRambaud](https://github.com/PierreRambaud)


### Changes in developer documentation
* [#401](https://github.com/PrestaShop/docs/pull/401): Update front-controllers.md. Thank you [@monumatik](https://github.com/monumatik)
* [#399](https://github.com/PrestaShop/docs/pull/399): Typo: set _PS_MODE_DEV_ to false instead of true. Thank you [@yannicka](https://github.com/yannicka)
* [#395](https://github.com/PrestaShop/docs/pull/395): Fix shortcodes following changes in Hugo 0.55, by [@eternoendless](https://github.com/eternoendless)
* [#393](https://github.com/PrestaShop/docs/pull/393): Move the "Documentation" section inside "Contributing", by [@eternoendless](https://github.com/eternoendless)
* [#391](https://github.com/PrestaShop/docs/pull/391): Update Hugo to 0.59.0, by [@eternoendless](https://github.com/eternoendless)


### Core Weekly Generator tool
* [#20](https://github.com/PrestaShop/core-weekly-generator/pull/20): Remove duplicate authors, by [@PierreRambaud](https://github.com/PierreRambaud)


### php-dev-tools
* [#16](https://github.com/PrestaShop/php-dev-tools/pull/16): Disable no_superfluous_phpdoc_tags in PHP-CS-Fixer config, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#15](https://github.com/PrestaShop/php-dev-tools/pull/15): Remove version from composer.json, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#14](https://github.com/PrestaShop/php-dev-tools/pull/14): Rename project content according to the repo name, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#13](https://github.com/PrestaShop/php-dev-tools/pull/13): Add header stamp to the project, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### ps_dataprivacy
* [#13](https://github.com/PrestaShop/ps_dataprivacy/pull/13): Rename Readme.md to README.md. Thank you [@yannicka](https://github.com/yannicka)


### Product Comments module
* [#40](https://github.com/PrestaShop/productcomments/pull/40): Update dependency for guzzlehttp/cache-subscriber, by [@jolelievre](https://github.com/jolelievre)


### Docker images
* [#191](https://github.com/PrestaShop/docker/pull/191): Update DEMO mode activation by altering defines_custom.php, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### php-ps-info
* [#5](https://github.com/PrestaShop/php-ps-info/pull/5): Add check for mbstring and bcmath + improve labels, by [@eternoendless](https://github.com/eternoendless)


### Classic-rocket theme
* [#108](https://github.com/PrestaShop/classic-rocket/pull/108): Remove duplicate of smarty block. Thank you [@micka-fdz](https://github.com/micka-fdz)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@PierreRambaud](https://github.com/PierreRambaud), [@monumatik](https://github.com/monumatik), [@matks](https://github.com/matks), [@Quetzacoalt91](https://github.com/Quetzacoalt91), [@yannicka](https://github.com/yannicka), [@WebXYAgency](https://github.com/WebXYAgency), [@jolelievre](https://github.com/jolelievre), [@boubkerbribri](https://github.com/boubkerbribri), [@atomiix](https://github.com/atomiix), [@eternoendless](https://github.com/eternoendless), [@marionf](https://github.com/marionf), [@matthieu-rolland](https://github.com/matthieu-rolland), [@LouiseBonnard](https://github.com/LouiseBonnard), [@micka-fdz](https://github.com/micka-fdz), [@sarjon](https://github.com/sarjon), [@Progi1984](https://github.com/Progi1984), [@Klemart3D](https://github.com/Klemart3D), [@tomas862](https://github.com/tomas862), [@rokaszygmantas](https://github.com/rokaszygmantas)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

---
layout: post
aliases: ["/news/coreweekly-week-46-2019.md"]
title:  "PrestaShop Core Weekly - Week 46 of 2019"
subtitle: "An inside look at the PrestaShop codebase"
date:   2019-11-20 10:00:00
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 11th to Sunday 17th of November 2019.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)


## A quick update about PrestaShop's GitHub issues and pull requests:

- [62 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2019-11-11..2019-11-17) have been created in the project repositories;
- [56 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2019-11-11..2019-11-17), including [5 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2019-11-11..2019-11-17) on the core;
- [55 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2019-11-11..2019-11-17) in the project repositories;
- [74 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2019-11-11..2019-11-17), including [51 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2019-11-11..2019-11-17).
        


## Code changes in the 'develop' branch


### Core
* [#16433](https://github.com/PrestaShop/PrestaShop/pull/16433): Update license headers, by [@matks](https://github.com/matks)
* [#16331](https://github.com/PrestaShop/PrestaShop/pull/16331): Add "total_shipping_tax_excl" and "total_shipping_tax_incl" in email data. Thank you [@yannicka](https://github.com/yannicka)
* [#16316](https://github.com/PrestaShop/PrestaShop/pull/16316): ImageManager::validateUpload : MimeType can't be check for SVG files, by [@Progi1984](https://github.com/Progi1984)
* [#16310](https://github.com/PrestaShop/PrestaShop/pull/16310): Add ps_dataprivacy, productcomments and ps_crossselling as native modules, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#16213](https://github.com/PrestaShop/PrestaShop/pull/16213): Make id order available. Thank you [@atomiix](https://github.com/atomiix)
* [#15902](https://github.com/PrestaShop/PrestaShop/pull/15902): Use the correct environment depending on what you are doing (dev, test, and prod), by [@PierreRambaud](https://github.com/PierreRambaud)


### Back office
* [#16394](https://github.com/PrestaShop/PrestaShop/pull/16394): Fix typo in condition. Thank you [@mvorisek](https://github.com/mvorisek)
* [#16392](https://github.com/PrestaShop/PrestaShop/pull/16392): Fixed the change the quantity of a free product in an order in the BO, by [@Progi1984](https://github.com/Progi1984)
* [#16375](https://github.com/PrestaShop/PrestaShop/pull/16375): Emails are not case sensitive, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#16360](https://github.com/PrestaShop/PrestaShop/pull/16360): Twig\HookExtension: Bugfix ob level in renderHooksArray. Thank you [@jnvsor](https://github.com/jnvsor)
* [#15915](https://github.com/PrestaShop/PrestaShop/pull/15915): Migration of International > Taxes > Tax rules page, by [@matks](https://github.com/matks)
* [#15229](https://github.com/PrestaShop/PrestaShop/pull/15229): Migration of Sell > Customers > Addresses page. Thank you [@RaimondasSapola](https://github.com/RaimondasSapola)
* [#14972](https://github.com/PrestaShop/PrestaShop/pull/14972): Add/Edit a currency with the CLDR implementation, by [@jolelievre](https://github.com/jolelievre)
* [#14288](https://github.com/PrestaShop/PrestaShop/pull/14288): Migrate Customer Service view. Thank you [@sarjon](https://github.com/sarjon)
* [#13716](https://github.com/PrestaShop/PrestaShop/pull/13716): Migrate Sell > Catalog > Catalog price rule create/edit action. Thank you [@zuk3975](https://github.com/zuk3975)


### Tests
* [#16414](https://github.com/PrestaShop/PrestaShop/pull/16414): Tests - Replace duplicated steps with foreach in taxes tests, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#16408](https://github.com/PrestaShop/PrestaShop/pull/16408): Tests - Replace duplicated steps with foreach in customers tests, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#16407](https://github.com/PrestaShop/PrestaShop/pull/16407): Tests - Replace duplicated steps with foreach in categories tests, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#16405](https://github.com/PrestaShop/PrestaShop/pull/16405): Tests - Replace duplicated steps with foreach in suppliers tests, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#16403](https://github.com/PrestaShop/PrestaShop/pull/16403): Tests - Replace duplicated steps with foreach for brands tests, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#16399](https://github.com/PrestaShop/PrestaShop/pull/16399): Tests - Delete replaces in tests Taxes, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#16395](https://github.com/PrestaShop/PrestaShop/pull/16395): Tests - Delete replaces in tests Customers, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#16387](https://github.com/PrestaShop/PrestaShop/pull/16387): Tests - Delete replaces in tests categories, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#16373](https://github.com/PrestaShop/PrestaShop/pull/16373): Tests - Using employees demo file for installation, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#16371](https://github.com/PrestaShop/PrestaShop/pull/16371): Tests - Delete replaces and use new methods instead in Supplier tests, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#16332](https://github.com/PrestaShop/PrestaShop/pull/16332): Tests - using same demo elements, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#16330](https://github.com/PrestaShop/PrestaShop/pull/16330): Tests - Delete replaces in tests and use new methods instead, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#16317](https://github.com/PrestaShop/PrestaShop/pull/16317): Only trigger deploy on cron task, and tests on push / pull requests, by [@PierreRambaud](https://github.com/PierreRambaud)


## Code changes in the '1.7.6.x' branch


### Core
* [#16335](https://github.com/PrestaShop/PrestaShop/pull/16335): update id_order_state at the right place. Thank you [@atomiix](https://github.com/atomiix)


### Back office
* [#16365](https://github.com/PrestaShop/PrestaShop/pull/16365): Viewed products - the date is showing product id - not a  date, by [@khouloudbelguith](https://github.com/khouloudbelguith)


### Front office
* [#16423](https://github.com/PrestaShop/PrestaShop/pull/16423): Use default attribute when no one are passed in front page, by [@PierreRambaud](https://github.com/PierreRambaud)


## Code changes in modules, themes & tools


### ps_currencyselector
* [#11](https://github.com/PrestaShop/ps_currencyselector/pull/11): Rebuild the url to avoid doublons, by [@jolelievre](https://github.com/jolelievre)


### QA nightly results
* [#10](https://github.com/PrestaShop/QANightlyResults/pull/10): Add jquery locally, change version system, by [@SimonGrn](https://github.com/SimonGrn)
* [#9](https://github.com/PrestaShop/QANightlyResults/pull/9): Inverted sorting, by [@SimonGrn](https://github.com/SimonGrn)
* [#8](https://github.com/PrestaShop/QANightlyResults/pull/8): Various fix, by [@SimonGrn](https://github.com/SimonGrn)


### Product Comments module
* [#44](https://github.com/PrestaShop/productcomments/pull/44): Update AFL-3.0 identifier, by [@jolelievre](https://github.com/jolelievre)
* [#43](https://github.com/PrestaShop/productcomments/pull/43): Update AFL-3.0 identifier, by [@jolelievre](https://github.com/jolelievre)
* [#41](https://github.com/PrestaShop/productcomments/pull/41): Merge dev to master for v4.0.1, by [@jolelievre](https://github.com/jolelievre)


### Changes in developer documentation
* [#403](https://github.com/PrestaShop/docs/pull/403): Update afl license, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#402](https://github.com/PrestaShop/docs/pull/402): Provide module and context properties in ModuleFrontController, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#400](https://github.com/PrestaShop/docs/pull/400): Add documentation for row actions, and clickable_row option, by [@jolelievre](https://github.com/jolelievre)
* [#396](https://github.com/PrestaShop/docs/pull/396): Improve style of notice blocks, by [@eternoendless](https://github.com/eternoendless)


### blockreassurance
* [#36](https://github.com/PrestaShop/blockreassurance/pull/36): Added a template for PullRequest, by [@Progi1984](https://github.com/Progi1984)
* [#35](https://github.com/PrestaShop/blockreassurance/pull/35): Permit to upload a SVG file as custom icon, by [@Progi1984](https://github.com/Progi1984)
* [#34](https://github.com/PrestaShop/blockreassurance/pull/34): Migrated JS & CSS assets from files to NPM & Webpack, by [@Progi1984](https://github.com/Progi1984)
* [#33](https://github.com/PrestaShop/blockreassurance/pull/33): Changed displayed images in second pack of images, by [@Progi1984](https://github.com/Progi1984)


### Cronjobs module
* [#49](https://github.com/PrestaShop/cronjobs/pull/49): Add missing domains, by [@LouiseBonnard](https://github.com/LouiseBonnard)


### Email Alerts module
* [#25](https://github.com/PrestaShop/ps_emailalerts/pull/25): Add missing domains, by [@LouiseBonnard](https://github.com/LouiseBonnard)


### Gamification module
* [#70](https://github.com/PrestaShop/gamification/pull/70): Add missing domains, by [@LouiseBonnard](https://github.com/LouiseBonnard)


### dateofdelivery
* [#18](https://github.com/PrestaShop/dateofdelivery/pull/18): Add missing domains, by [@LouiseBonnard](https://github.com/LouiseBonnard)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@matks](https://github.com/matks), [@PierreRambaud](https://github.com/PierreRambaud), [@boubkerbribri](https://github.com/boubkerbribri), [@jolelievre](https://github.com/jolelievre), [@mvorisek](https://github.com/mvorisek), [@Progi1984](https://github.com/Progi1984), [@SimonGrn](https://github.com/SimonGrn), [@khouloudbelguith](https://github.com/khouloudbelguith), [@jnvsor](https://github.com/jnvsor), [@Quetzacoalt91](https://github.com/Quetzacoalt91), [@atomiix](https://github.com/atomiix), [@yannicka](https://github.com/yannicka), [@eternoendless](https://github.com/eternoendless), [@LouiseBonnard](https://github.com/LouiseBonnard), [@RaimondasSapola](https://github.com/RaimondasSapola), [@sarjon](https://github.com/sarjon), [@zuk3975](https://github.com/zuk3975)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

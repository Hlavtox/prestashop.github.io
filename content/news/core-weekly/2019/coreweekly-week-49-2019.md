---
layout: post
aliases: ["/news/coreweekly-week-49-2019"]
title:  "PrestaShop Core Weekly - Week 49 of 2019"
subtitle: "An inside look at the PrestaShop codebase"
date:   2019-12-13
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 2nd to Sunday 8th of December 2019.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)

## General messages

Dear Developers,

We were at [Paris Open Source Summit last week](https://www.opensourcesummit.paris/), and our developer advocate, Antoine Thomas, spoke about his [open source project activities and maturity dashboard](https://github.com/PrestaShop/open-source/tree/master/templates). We also are very glad to announce that we have won the [International Development Award](https://lesacteursdulibre.com/portfolio/prix-developpement-international/) at this event.


## A quick update about PrestaShop's GitHub issues and pull requests:

- [63 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2019-12-02..2019-12-08) have been created in the project repositories;
- [53 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2019-12-02..2019-12-08), including [8 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2019-12-02..2019-12-08) on the core;
- [59 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2019-12-02..2019-12-08) in the project repositories;
- [49 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2019-12-02..2019-12-08), including [40 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2019-12-02..2019-12-08).
        

## Code changes in the 'develop' branch


### Core
* [#16635](https://github.com/PrestaShop/PrestaShop/pull/16635): Fix discount calculation if two gift-cartrules exist for the same product.. Thank you [@Hlavtox](https://github.com/Hlavtox)

### Back office
* [#16690](https://github.com/PrestaShop/PrestaShop/pull/16690): Add Khmer language, by [@LouiseBonnard](https://github.com/LouiseBonnard)
* [#16662](https://github.com/PrestaShop/PrestaShop/pull/16662): Fix PHP docblocks. Thank you [@mfurga](https://github.com/mfurga)
* [#16570](https://github.com/PrestaShop/PrestaShop/pull/16570): Provides several UX improvements for order pages and allows to change order addresses, by [@matks](https://github.com/matks)
* [#16552](https://github.com/PrestaShop/PrestaShop/pull/16552): Add generic ButtonBulkAction and javascript to handle open in tabs, by [@jolelievre](https://github.com/jolelievre)
* [#16255](https://github.com/PrestaShop/PrestaShop/pull/16255): Migration of order view page messages block. Thank you [@tomas862](https://github.com/tomas862)
* [#16074](https://github.com/PrestaShop/PrestaShop/pull/16074): Move the customer search by id to the first place. Thank you [@levyn](https://github.com/levyn)


### Front office
* [#16638](https://github.com/PrestaShop/PrestaShop/pull/16638): Fix logic and display of customer's cart rules. Thank you [@Hlavtox](https://github.com/Hlavtox)
* [#16528](https://github.com/PrestaShop/PrestaShop/pull/16528): Changing links block style in carrier process. Thank you [@NeOMakinG](https://github.com/NeOMakinG)
* [#16524](https://github.com/PrestaShop/PrestaShop/pull/16524): Switching select of ps_brandlist to a bootstrap dropdown. Thank you [@NeOMakinG](https://github.com/NeOMakinG)


### Installer
* [#16527](https://github.com/PrestaShop/PrestaShop/pull/16527): Check memory_limit during installation, by [@PierreRambaud](https://github.com/PierreRambaud)


### Tests
* [#16727](https://github.com/PrestaShop/PrestaShop/pull/16727): Functional tests - Fix test CRUD profile, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#16721](https://github.com/PrestaShop/PrestaShop/pull/16721): Functional tests - Fix echange rate on test currency, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#16708](https://github.com/PrestaShop/PrestaShop/pull/16708): Tests - Fix eslint errors on linkchecker, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#16705](https://github.com/PrestaShop/PrestaShop/pull/16705): Functional tests - Add test 'Bulk Edit Quantity in stocks', by [@boubkerbribri](https://github.com/boubkerbribri)
* [#16699](https://github.com/PrestaShop/PrestaShop/pull/16699): Functional Tests - add test create official currency, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#16681](https://github.com/PrestaShop/PrestaShop/pull/16681): Tests - Fix errors in functional tests, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#16679](https://github.com/PrestaShop/PrestaShop/pull/16679): Functional Tests - Fix describe message for generate invoice by date/status. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#16674](https://github.com/PrestaShop/PrestaShop/pull/16674): Functional Tests - Add BO tests for invoice options Enable/Disable. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#16666](https://github.com/PrestaShop/PrestaShop/pull/16666): Tests - Running tests with user root , by [@boubkerbribri](https://github.com/boubkerbribri)
* [#16659](https://github.com/PrestaShop/PrestaShop/pull/16659): Tests Update README.md and DOCKER.md, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#16655](https://github.com/PrestaShop/PrestaShop/pull/16655): Functional Tests - Add BO tests for generate invoice by status. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#16647](https://github.com/PrestaShop/PrestaShop/pull/16647): Tests - Using pptruser to run tests with download, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#16644](https://github.com/PrestaShop/PrestaShop/pull/16644): Tests - Fix logout used in Employee tests, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#16612](https://github.com/PrestaShop/PrestaShop/pull/16612): Functional tests - Adding test update Quantity on catalog-stocks page, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#16566](https://github.com/PrestaShop/PrestaShop/pull/16566): Functional Tests - Add BO tests for generate invoice by date. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)


## Code changes in the '1.7.6.x' branch (for 1.7.6.3)


### Back office
* [#16648](https://github.com/PrestaShop/PrestaShop/pull/16648): Fix customer statuses not being able to toggle when optin field is required, by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#16294](https://github.com/PrestaShop/PrestaShop/pull/16294): Fix email not translated when installing a new language. Thank you [@atomiix](https://github.com/atomiix)


## Code changes in modules, themes & tools


### Google Analytics module
* [#38](https://github.com/PrestaShop/ps_googleanalytics/pull/38): Release v3.2.0 of Google Analytics module, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Prestashop UI Kit
* [#72](https://github.com/PrestaShop/prestashop-ui-kit/pull/72): Adding stylelint to the UI Kit. Thank you [@NeOMakinG](https://github.com/NeOMakinG)


### Changes in developer documentation
* [#416](https://github.com/PrestaShop/docs/pull/416): twig file syntax error fixed. Thank you [@dheerajwebkul](https://github.com/dheerajwebkul)


### Theme custo module
* [#19](https://github.com/PrestaShop/ps_themecusto/pull/19): Make sure the dropzone js is loaded before adding the dropzone component, by [@PierreRambaud](https://github.com/PierreRambaud)


### Currency selector module
* [#14](https://github.com/PrestaShop/ps_currencyselector/pull/14): Update to version 2.0.1, by [@jolelievre](https://github.com/jolelievre)


### Supplier list module
* [#4](https://github.com/PrestaShop/ps_supplierlist/pull/4): Changing suppliers select to bootstrap dropdown. Thank you [@NeOMakinG](https://github.com/NeOMakinG)


### Brand list module
* [#6](https://github.com/PrestaShop/ps_brandlist/pull/6): Changing brands select into boostrap dropdown. Thank you [@NeOMakinG](https://github.com/NeOMakinG)


### Block reassurance module
* [#37](https://github.com/PrestaShop/blockreassurance/pull/37): Added the ability to remove a block, by [@Progi1984](https://github.com/Progi1984)


### Classic-rocket theme
* [#110](https://github.com/PrestaShop/classic-rocket/pull/110): Smarty templates improvement. Thank you [@micka-fdz](https://github.com/micka-fdz)


### Prestafraud module
* [#12](https://github.com/PrestaShop/prestafraud/pull/12): Add missing domains, by [@LouiseBonnard](https://github.com/LouiseBonnard)


### Emails manager module
* [#10](https://github.com/PrestaShop/ps_emailsmanager/pull/10): Add missing domains, by [@LouiseBonnard](https://github.com/LouiseBonnard)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@boubkerbribri](https://github.com/boubkerbribri), [@LouiseBonnard](https://github.com/LouiseBonnard), [@Quetzacoalt91](https://github.com/Quetzacoalt91), [@nesrineabdmouleh](https://github.com/nesrineabdmouleh), [@NeOMakinG](https://github.com/NeOMakinG), [@mfurga](https://github.com/mfurga), [@matthieu-rolland](https://github.com/matthieu-rolland), [@dheerajwebkul](https://github.com/dheerajwebkul), [@Hlavtox](https://github.com/Hlavtox), [@matks](https://github.com/matks), [@PierreRambaud](https://github.com/PierreRambaud), [@jolelievre](https://github.com/jolelievre), [@Progi1984](https://github.com/Progi1984), [@ziegenberg](https://github.com/ziegenberg), [@atomiix](https://github.com/atomiix), [@micka-fdz](https://github.com/micka-fdz), [@tomas862](https://github.com/tomas862), [@levyn](https://github.com/levyn)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!



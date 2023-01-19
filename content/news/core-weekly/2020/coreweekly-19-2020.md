---
layout: post
aliases: ["/news/coreweekly-19-2020"]
title:  "PrestaShop Core Weekly - Week 19 of 2020"
subtitle: "An inside look at the PrestaShop codebase"
date:   2020-05-12
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
icon: icon-calendar
tags:
 - core-monthly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 04 to Sunday 10 of May 2020.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)

## General messages

1.7.7 beta is built and currently being checked by the QA team before the release.


## A quick update about PrestaShop's GitHub issues and pull requests:

- [78 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2020-05-04..2020-05-10) have been created in the project repositories;
- [57 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2020-05-04..2020-05-10), including [2 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2020-05-04..2020-05-10) on the core;
- [60 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2020-05-04..2020-05-10) in the project repositories;
- [61 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2020-05-04..2020-05-10), including [34 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2020-05-04..2020-05-10).
        


## Code changes in the 'develop' branch


### Core
* [#18988](https://github.com/PrestaShop/PrestaShop/pull/18988): Add phpdoc to class Curve, by [@matks](https://github.com/matks)
* [#18979](https://github.com/PrestaShop/PrestaShop/pull/18979): Update Smarty 3.1.34 -> 3.1.36, by [@matks](https://github.com/matks)


### Back office
* [#18986](https://github.com/PrestaShop/PrestaShop/pull/18986): Remove useless old call to addons, by [@matks](https://github.com/matks)


### Tests
* [#19025](https://github.com/PrestaShop/PrestaShop/pull/19025): Functional tests - Increase timeout for docker puppeteer, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#19006](https://github.com/PrestaShop/PrestaShop/pull/19006): Functional tests - Fix change selectors, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#18962](https://github.com/PrestaShop/PrestaShop/pull/18962): Use progress format for Behat, by [@matks](https://github.com/matks)


### Merge
* [#18998](https://github.com/PrestaShop/PrestaShop/pull/18998): Merge 1.7.7.x into develop - 06/05/2020, by [@matks](https://github.com/matks)
* [#18918](https://github.com/PrestaShop/PrestaShop/pull/18918): Merge branch "1.7.7.x" into "develop", by [@Progi1984](https://github.com/Progi1984)


## Code changes in the '1.7.7.x' branch


### Tests
* [#19004](https://github.com/PrestaShop/PrestaShop/pull/19004): Functional tests - Sort suppliers table. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#18990](https://github.com/PrestaShop/PrestaShop/pull/18990): Functional tests - Enable/Disable log emails. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#18977](https://github.com/PrestaShop/PrestaShop/pull/18977): Functional tests - Test pages pagination. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#18963](https://github.com/PrestaShop/PrestaShop/pull/18963): Functional tests - Test page category pagination. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#18899](https://github.com/PrestaShop/PrestaShop/pull/18899): Functional tests - Country restrictions. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#18896](https://github.com/PrestaShop/PrestaShop/pull/18896): Functional tests - Change selectors for design pages, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#18886](https://github.com/PrestaShop/PrestaShop/pull/18886): Functional tests - Fix test invoices and products settings, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#18877](https://github.com/PrestaShop/PrestaShop/pull/18877): Functional tests - Change selectors for FO pages. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#18871](https://github.com/PrestaShop/PrestaShop/pull/18871): Functional tests - Update default currency. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#18868](https://github.com/PrestaShop/PrestaShop/pull/18868): Functional tests - Change selectors for modules pages, by [@boubkerbribri](https://github.com/boubkerbribri)


## Code changes in modules, themes & tools


### Google Analytics module
* [#49](https://github.com/PrestaShop/ps_googleanalytics/pull/49): Make compatible 1.6, by [@apacios](https://github.com/apacios)


### Changes in developer documentation
* [#530](https://github.com/PrestaShop/docs/pull/530): [Testing] Add fix to web acceptance test docs, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#526](https://github.com/PrestaShop/docs/pull/526): Update PR process as it has evolved, by [@matks](https://github.com/matks)
* [#525](https://github.com/PrestaShop/docs/pull/525): Fix headings in Patch release lifecycle page, by [@matks](https://github.com/matks)
* [#524](https://github.com/PrestaShop/docs/pull/524): Copy release lifecycle posts into devdoc, by [@matks](https://github.com/matks)
* [#522](https://github.com/PrestaShop/docs/pull/522): Missing use of FolderThemeScanner. Thank you [@Leenwt](https://github.com/Leenwt)
* [#521](https://github.com/PrestaShop/docs/pull/521): Use Apache httpd rather than httpd for better SEO, by [@matks](https://github.com/matks)
* [#505](https://github.com/PrestaShop/docs/pull/505): Improve web acceptance contribution doc, by [@boubkerbribri](https://github.com/boubkerbribri)


### PrestaShop Specifications
* [#117](https://github.com/PrestaShop/prestashop-specs/pull/117): Rename licence to LICENSE. Thank you [@sam-pires](https://github.com/sam-pires)
* [#116](https://github.com/PrestaShop/prestashop-specs/pull/116): Create licence. Thank you [@sam-pires](https://github.com/sam-pires)
* [#114](https://github.com/PrestaShop/prestashop-specs/pull/114): Improvements for UX display of catalog price rule spec document, by [@matks](https://github.com/matks)


### PHP Developer Tools
* [#23](https://github.com/PrestaShop/php-dev-tools/pull/23): Improve declaration of _PS_VERSION_ constant, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### PSGDPR
* [#84](https://github.com/PrestaShop/psgdpr/pull/84): Always check if anonymousCustomer is set, by [@PierreRambaud](https://github.com/PierreRambaud)


### PrestaShop-webservice-lib
* [#66](https://github.com/PrestaShop/PrestaShop-webservice-lib/pull/66): Fix typos in PSWebServiceLibrary.php. Thank you [@pgrimaud](https://github.com/pgrimaud)
* [#53](https://github.com/PrestaShop/PrestaShop-webservice-lib/pull/53): Add 'schema' to resources, then you can use $opt['schema'] = 'blank';. Thank you [@marekhanus](https://github.com/marekhanus)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@boubkerbribri](https://github.com/boubkerbribri), [@apacios](https://github.com/apacios), [@nesrineabdmouleh](https://github.com/nesrineabdmouleh), [@matks](https://github.com/matks), [@sam-pires](https://github.com/sam-pires), [@Quetzacoalt91](https://github.com/Quetzacoalt91), [@Leenwt](https://github.com/Leenwt), [@Progi1984](https://github.com/Progi1984), [@PierreRambaud](https://github.com/PierreRambaud), [@pgrimaud](https://github.com/pgrimaud), [@marekhanus](https://github.com/marekhanus)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

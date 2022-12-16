---
layout: post
aliases: ["/news/coreweekly-39-2020"]
title:  "PrestaShop Core Weekly - Week 39 of 2020"
subtitle: "An inside look at the PrestaShop codebase"
date:   2020-09-29
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
twitter_image: /assets/images/theme/banner-core-weekly.jpg
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 21th to Sunday 27th of September 2020.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)

## General messages

Dear Developers,

A lot of things happened last week!

First, PrestaShop [1.7.6.8](https://build.prestashop.com/news/prestashop-1-7-6-8-maintenance-release/) has been released. don't forget to update as this patch version fixes 3 security issues.

Second, the road is now open to deliver PrestaShop 1.7.7.0 first Release Candidate. A first build has been achieved and delivered to QA team to run the tests campaign before publishing it.

Finally, a [2 years old bug](https://github.com/PrestaShop/PrestaShop/issues/9659) in the profiler, awaited by a lot of users has finally [been fixed](https://github.com/PrestaShop/PrestaShop/pull/20673) in `develop` branch!


## Releases

* [PrestaShop](https://github.com/PrestaShop/PrestaShop): [PrestaShop 1.7.6.8](https://github.com/PrestaShop/PrestaShop/releases/tag/1.7.6.8)
* [Dashproducts](https://github.com/PrestaShop/dashproducts): [v2.1.1](https://github.com/PrestaShop/dashproducts/releases/tag/v2.1.1)


## A quick update about PrestaShop's GitHub issues and pull requests:

- [59 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2020-09-21..2020-09-27) have been created in the project repositories;
- [57 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2020-09-21..2020-09-27), including [16 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2020-09-21..2020-09-27) on the core;
- [76 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2020-09-21..2020-09-27) in the project repositories;
- [69 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2020-09-21..2020-09-27), including [66 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2020-09-21..2020-09-27).



## Code changes in the 'develop' branch


### Core
* [#21076](https://github.com/PrestaShop/PrestaShop/pull/21076): Ignore whole Netbeans project, not only private. Thank you [@mvorisek](https://github.com/mvorisek)
* [#21042](https://github.com/PrestaShop/PrestaShop/pull/21042): Changed PHPDoc of Tax's getProductTaxRate to more accurate.. Thank you [@stijnstroeve](https://github.com/stijnstroeve)
* [#20987](https://github.com/PrestaShop/PrestaShop/pull/20987): Wrap language into cdata for blank pattern, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#20849](https://github.com/PrestaShop/PrestaShop/pull/20849): Ability to enable and disable Hooks. Thank you [@PululuK](https://github.com/PululuK)
* [#20673](https://github.com/PrestaShop/PrestaShop/pull/20673): Refactor the profiling to make it works with Hook and Modules, by [@PierreRambaud](https://github.com/PierreRambaud)


### Back office
* [#21086](https://github.com/PrestaShop/PrestaShop/pull/21086): Grid bulk delete confirmation modal - Shop Parameters > Traffic SEO URLs, by [@sowbiba](https://github.com/sowbiba)
* [#21085](https://github.com/PrestaShop/PrestaShop/pull/21085): Grid bulk delete confirmation modal - Shop Parameters > Contacts, by [@sowbiba](https://github.com/sowbiba)
* [#21084](https://github.com/PrestaShop/PrestaShop/pull/21084): Grid bulk delete confirmation modal - Advanced Parameters > Webservice keys, by [@sowbiba](https://github.com/sowbiba)
* [#21083](https://github.com/PrestaShop/PrestaShop/pull/21083): Grid bulk delete confirmation modal - Advanced Parameters > DB > Backups, by [@sowbiba](https://github.com/sowbiba)
* [#21082](https://github.com/PrestaShop/PrestaShop/pull/21082): Grid bulk delete confirmation modal - Advanced Parameters > DB > SQL Requests, by [@sowbiba](https://github.com/sowbiba)
* [#21081](https://github.com/PrestaShop/PrestaShop/pull/21081): Grid bulk delete confirmation modal - Advanced Parameters > Team > Profiles, by [@sowbiba](https://github.com/sowbiba)
* [#21080](https://github.com/PrestaShop/PrestaShop/pull/21080): Grid bulk delete confirmation modal - Advanced Parameters > Team > Employees, by [@sowbiba](https://github.com/sowbiba)
* [#21079](https://github.com/PrestaShop/PrestaShop/pull/21079): Grid bulk delete confirmation modal - Advanced Parameters > Emails, by [@sowbiba](https://github.com/sowbiba)
* [#21074](https://github.com/PrestaShop/PrestaShop/pull/21074): Function mobileNav has no arguments. Thank you [@davidglezz](https://github.com/davidglezz)
* [#21073](https://github.com/PrestaShop/PrestaShop/pull/21073): Improve calendar Javascript setup. Thank you [@davidglezz](https://github.com/davidglezz)
* [#21072](https://github.com/PrestaShop/PrestaShop/pull/21072): Simplify computeMappingBetweenOldAndNewPositions(). Thank you [@davidglezz](https://github.com/davidglezz)
* [#21033](https://github.com/PrestaShop/PrestaShop/pull/21033): Grid row delete confirmation modal - Customer service > Order messages, by [@sowbiba](https://github.com/sowbiba)
* [#20584](https://github.com/PrestaShop/PrestaShop/pull/20584): Split BO css into multiple bundles, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#20261](https://github.com/PrestaShop/PrestaShop/pull/20261): Modify adresses listing in Customer page to use Grid instead, by [@sowbiba](https://github.com/sowbiba)
* [#19703](https://github.com/PrestaShop/PrestaShop/pull/19703): Handle empty states for category grids, by [@atomiix](https://github.com/atomiix)


### Front office
* [#21011](https://github.com/PrestaShop/PrestaShop/pull/21011): Add product link in summary cart . Thank you [@PululuK](https://github.com/PululuK)
* [#20941](https://github.com/PrestaShop/PrestaShop/pull/20941): Validate password only if not empty, fixing Guest Checkout, by [@matks](https://github.com/matks)
* [#20338](https://github.com/PrestaShop/PrestaShop/pull/20338): Fix guest tracking without friendly URLs. Thank you [@SuichiM](https://github.com/SuichiM)
* [#20233](https://github.com/PrestaShop/PrestaShop/pull/20233): Fix order history font-size and contrast. Thank you [@davidglezz](https://github.com/davidglezz)


### Tests
* [#20707](https://github.com/PrestaShop/PrestaShop/pull/20707): Fix ReflexionHelper class name. Thank you [@mvorisek](https://github.com/mvorisek)


## Code changes in the '1.7.7.x' branch


### Core
* [#20378](https://github.com/PrestaShop/PrestaShop/pull/20378): Use Computing precision instead of hardcoded 2, by [@matks](https://github.com/matks)


### Back office
* [#21048](https://github.com/PrestaShop/PrestaShop/pull/21048): Fix [BO- Stores page] Sort by post code not working. Thank you [@PululuK](https://github.com/PululuK)
* [#21045](https://github.com/PrestaShop/PrestaShop/pull/21045): Fix Features page throwing an exception after specific steps are made, by [@atomiix](https://github.com/atomiix)
* [#21031](https://github.com/PrestaShop/PrestaShop/pull/21031): Fix bad range error when setting free shipping on a previously not free shipping carrier, by [@atomiix](https://github.com/atomiix)
* [#21025](https://github.com/PrestaShop/PrestaShop/pull/21025): Make legacy parameters from routing accessible in migrated pages, by [@jolelievre](https://github.com/jolelievre)
* [#20760](https://github.com/PrestaShop/PrestaShop/pull/20760): Add Order - View customer details : Check if nav-bar exist to avoid console errors, by [@sowbiba](https://github.com/sowbiba)
* [#20628](https://github.com/PrestaShop/PrestaShop/pull/20628): Restore selectors in Order Page for GDPR to make GDPR module compliant with 1.7.7.0, by [@matks](https://github.com/matks)


### Tests
* [#21139](https://github.com/PrestaShop/PrestaShop/pull/21139): Change faker for locations tests, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#21123](https://github.com/PrestaShop/PrestaShop/pull/21123): Add test 'Sort and pagination attributes'. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#21122](https://github.com/PrestaShop/PrestaShop/pull/21122): Add github action to check eslint and step identifier doubles for UI tests, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#21116](https://github.com/PrestaShop/PrestaShop/pull/21116): Fix Error in last PR to force playwright 1.0.2, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#21097](https://github.com/PrestaShop/PrestaShop/pull/21097): Downgrade playwright to version 1.0.2, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#21090](https://github.com/PrestaShop/PrestaShop/pull/21090): Unskip test 'Sort by post code' in stores page after fixing issue, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#21089](https://github.com/PrestaShop/PrestaShop/pull/21089): Increase timeout for 'Sort' tests, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#21064](https://github.com/PrestaShop/PrestaShop/pull/21064): Add test 'Crud carrier'. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#20935](https://github.com/PrestaShop/PrestaShop/pull/20935): Add test 'Bulk actions countries', by [@boubkerbribri](https://github.com/boubkerbribri)


## Code changes in the '1.7.6.x' branch


### Core
* [#21138](https://github.com/PrestaShop/PrestaShop/pull/21138): Add changelog for the 1.7.6.8 version, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#21124](https://github.com/PrestaShop/PrestaShop/pull/21124): Bump version to 1.7.6.8, bump contactform version, by [@PierreRambaud](https://github.com/PierreRambaud)


## Code changes in modules, themes & tools


### Category tree links module
* [#38](https://github.com/PrestaShop/ps_categorytree/pull/38): Improve project, by [@Progi1984](https://github.com/Progi1984)


### Customer account links module
* [#29](https://github.com/PrestaShop/ps_customeraccountlinks/pull/29): Improve project, by [@Progi1984](https://github.com/Progi1984)


### Cross-selling module
* [#14](https://github.com/PrestaShop/ps_crossselling/pull/14): Improve project, by [@Progi1984](https://github.com/Progi1984)


### Docker images
* [#229](https://github.com/PrestaShop/docker/pull/229): Release 1.7.6.8, by [@PierreRambaud](https://github.com/PierreRambaud)


### Nightly board
* [#47](https://github.com/PrestaShop/nightly-board/pull/47): Hide download report when url is undefined, by [@NeOMakinG](https://github.com/NeOMakinG)


### Changes in developer documentation
* [#749](https://github.com/PrestaShop/docs/pull/749): Remove duplicate phrase. Thank you [@moncef-essid](https://github.com/moncef-essid)
* [#748](https://github.com/PrestaShop/docs/pull/748): Fix spelling mistake. Thank you [@moncef-essid](https://github.com/moncef-essid)
* [#747](https://github.com/PrestaShop/docs/pull/747): Fix spelling mistake. Thank you [@moncef-essid](https://github.com/moncef-essid)
* [#746](https://github.com/PrestaShop/docs/pull/746): Spelling mistake. Thank you [@moncef-essid](https://github.com/moncef-essid)
* [#745](https://github.com/PrestaShop/docs/pull/745): spelling mistake. Thank you [@moncef-essid](https://github.com/moncef-essid)
* [#744](https://github.com/PrestaShop/docs/pull/744): Spelling mistake. Thank you [@moncef-essid](https://github.com/moncef-essid)
* [#743](https://github.com/PrestaShop/docs/pull/743): Fix some typos, by [@atomiix](https://github.com/atomiix)
* [#742](https://github.com/PrestaShop/docs/pull/742): Correcting parameter name for postcode instead of county. Thank you [@moncef-essid](https://github.com/moncef-essid)
* [#741](https://github.com/PrestaShop/docs/pull/741): Add quick summary about github labels and processes, by [@matks](https://github.com/matks)
* [#740](https://github.com/PrestaShop/docs/pull/740): Correcting the image title. Thank you [@moncef-essid](https://github.com/moncef-essid)
* [#739](https://github.com/PrestaShop/docs/pull/739): Correcting functions name associated to http verb. Thank you [@moncef-essid](https://github.com/moncef-essid)
* [#738](https://github.com/PrestaShop/docs/pull/738): Fix path error in template layouts page. Thank you [@moncef-essid](https://github.com/moncef-essid)
* [#737](https://github.com/PrestaShop/docs/pull/737): Mention jQuery.attr has changed in 1.7.7, by [@matks](https://github.com/matks)


### Core Weekly Generator tool
* [#51](https://github.com/PrestaShop/core-weekly-generator/pull/51): Dont use zero-padded decimal for day number when using week number input, by [@matks](https://github.com/matks)


### Legal Compliance
* [#69](https://github.com/PrestaShop/ps_legalcompliance/pull/69): FO: Improve display if long text in displayProductPriceBlock. Thank you [@idnovate](https://github.com/idnovate)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@Progi1984](https://github.com/Progi1984), [@boubkerbribri](https://github.com/boubkerbribri), [@PierreRambaud](https://github.com/PierreRambaud), [@NeOMakinG](https://github.com/NeOMakinG), [@nesrineabdmouleh](https://github.com/nesrineabdmouleh), [@moncef-essid](https://github.com/moncef-essid), [@sowbiba](https://github.com/sowbiba), [@matks](https://github.com/matks), [@atomiix](https://github.com/atomiix), [@mvorisek](https://github.com/mvorisek), [@davidglezz](https://github.com/davidglezz), [@PululuK](https://github.com/PululuK), [@stijnstroeve](https://github.com/stijnstroeve), [@jolelievre](https://github.com/jolelievre), [@SuichiM](https://github.com/SuichiM), [@idnovate](https://github.com/idnovate)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

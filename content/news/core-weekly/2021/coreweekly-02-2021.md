---
layout: post
aliases: ["/news/coreweekly-02-2021"]
title:  "PrestaShop Core Weekly - Week 2 of 2021"
subtitle: "An inside look at the PrestaShop codebase"
date:   2021-01-18
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
twitter_image: /assets/images/theme/banner-core-weekly.jpg
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 11th to Sunday 17th of January 2021.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)

## Releases

* [ps_categorytree](https://github.com/PrestaShop/ps_categorytree) module: [v2.0.1](https://github.com/PrestaShop/ps_categorytree/releases/tag/v2.0.1)
* [ps_searchbar](https://github.com/PrestaShop/ps_searchbar) module: [v2.1.0](https://github.com/PrestaShop/ps_searchbar/releases/tag/v2.1.0)
* [ps_qualityassurance](https://github.com/PrestaShop/ps_qualityassurance) module: [v1.1.1](https://github.com/PrestaShop/ps_qualityassurance/releases/tag/v1.1.1)


## A quick update about PrestaShop's GitHub issues and pull requests:

- [77 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2021-01-11..2021-01-17) have been created in the project repositories;
- [76 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2021-01-11..2021-01-17), including [15 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2021-01-11..2021-01-17) on the core;
- [86 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2021-01-11..2021-01-17) in the project repositories;
- [100 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2021-01-11..2021-01-17), including [90 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2021-01-11..2021-01-17).



## Code changes in the 'develop' branch


### Core
* [#22808](https://github.com/PrestaShop/PrestaShop/pull/22808): Do not log addons requests urls, we don't want it in logs, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#22780](https://github.com/PrestaShop/PrestaShop/pull/22780): Improve Category::getProducts : Avoid short variable names. Thank you [@PululuK](https://github.com/PululuK)
* [#22686](https://github.com/PrestaShop/PrestaShop/pull/22686): Add more data to actionProductCancel hook. Thank you [@Hlavtox](https://github.com/Hlavtox)
* [#22555](https://github.com/PrestaShop/PrestaShop/pull/22555): Move Product pack classes in Pack subdomain in adapter, by [@matks](https://github.com/matks)
* [#22223](https://github.com/PrestaShop/PrestaShop/pull/22223): Be able to don't add anchor in the URL for getProductLink method, by [@PierreRambaud](https://github.com/PierreRambaud)


### Back office
* [#22849](https://github.com/PrestaShop/PrestaShop/pull/22849): Move customization into product subdomain namespace, by [@jolelievre](https://github.com/jolelievre)
* [#22807](https://github.com/PrestaShop/PrestaShop/pull/22807): Adjust payment page responsive, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#22777](https://github.com/PrestaShop/PrestaShop/pull/22777): Allow extra fields in product combinations. Thank you [@Renrhaf](https://github.com/Renrhaf)
* [#22766](https://github.com/PrestaShop/PrestaShop/pull/22766): Improve ProductCommandBuilderInterface for multi return, by [@jolelievre](https://github.com/jolelievre)
* [#22761](https://github.com/PrestaShop/PrestaShop/pull/22761): Fix mobile dropdown of multishop context on default theme of the BO, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#22742](https://github.com/PrestaShop/PrestaShop/pull/22742): Fix some width and spacing of kpis pan, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#22736](https://github.com/PrestaShop/PrestaShop/pull/22736): Update the UIKit to the latest release, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#22698](https://github.com/PrestaShop/PrestaShop/pull/22698): Module manager page needs some adjusts on mobile, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#22691](https://github.com/PrestaShop/PrestaShop/pull/22691): Fix stock page responsive, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#22619](https://github.com/PrestaShop/PrestaShop/pull/22619): Fix invisible input in SEO Options, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#22436](https://github.com/PrestaShop/PrestaShop/pull/22436): Update legacy pages style in order to collapse a bit more to the UIKit, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#22403](https://github.com/PrestaShop/PrestaShop/pull/22403): Do not use raw in DataColumn, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#22378](https://github.com/PrestaShop/PrestaShop/pull/22378): Get rid of empty string of redirect type from database structure. Thank you [@zuk3975](https://github.com/zuk3975)
* [#22349](https://github.com/PrestaShop/PrestaShop/pull/22349): Hide recommended modules and help on mobile view in the BO, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#22316](https://github.com/PrestaShop/PrestaShop/pull/22316): Add confirm modal on module update, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#21249](https://github.com/PrestaShop/PrestaShop/pull/21249): Make sure the force ssl is used in Cookie class when we are in admin context, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#19996](https://github.com/PrestaShop/PrestaShop/pull/19996): Simplify Suppliers form. Thank you [@JevgenijVisockij](https://github.com/JevgenijVisockij)


### Front office
* [#22749](https://github.com/PrestaShop/PrestaShop/pull/22749): Remove useless redirection on shop logo in multilingual context. Thank you [@jf-viguier](https://github.com/jf-viguier)
* [#21491](https://github.com/PrestaShop/PrestaShop/pull/21491): Add id_product_attribute to order conf  mails. Thank you [@IAmWebSA](https://github.com/IAmWebSA)


### Tests
* [#22795](https://github.com/PrestaShop/PrestaShop/pull/22795): Fix phpstan CI on develop, by [@matks](https://github.com/matks)
* [#22793](https://github.com/PrestaShop/PrestaShop/pull/22793): Upgrade playwright to 1.6.2. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#22764](https://github.com/PrestaShop/PrestaShop/pull/22764): Introduce phpstan extension, by [@matks](https://github.com/matks)
* [#22738](https://github.com/PrestaShop/PrestaShop/pull/22738): Add new FO test 'CRUD Address in FO', by [@boubkerbribri](https://github.com/boubkerbribri)
* [#22717](https://github.com/PrestaShop/PrestaShop/pull/22717): Change import file test to import attributes instead of customers. Thank you [@SD1982](https://github.com/SD1982)
* [#22707](https://github.com/PrestaShop/PrestaShop/pull/22707): Add test 'Filter, sort and pagination currencies'. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)


## Code changes in the '1.7.7.x' branch


### Back office
* [#22688](https://github.com/PrestaShop/PrestaShop/pull/22688): Prevent HookDataCollector unserialize() to throw an exception, by [@atomiix](https://github.com/atomiix)
* [#22685](https://github.com/PrestaShop/PrestaShop/pull/22685): Create Order - Cart details modal - Fix refresh for cart total, by [@sowbiba](https://github.com/sowbiba)
* [#22673](https://github.com/PrestaShop/PrestaShop/pull/22673): PerfectScrollBar needs available element, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#22542](https://github.com/PrestaShop/PrestaShop/pull/22542): Handle case where product location is a boolean, by [@atomiix](https://github.com/atomiix)
* [#22367](https://github.com/PrestaShop/PrestaShop/pull/22367): Order view - Refresh shipping tab when product is added, removed or updated, by [@sowbiba](https://github.com/sowbiba)


### Front office
* [#22518](https://github.com/PrestaShop/PrestaShop/pull/22518): Define when a voucher should be displayed in 'Your vouchers', by [@atomiix](https://github.com/atomiix)


### Installer
* [#22735](https://github.com/PrestaShop/PrestaShop/pull/22735): Fix installation carrier delay Error for Persian Language, by [@matks](https://github.com/matks)


### Tests
* [#22792](https://github.com/PrestaShop/PrestaShop/pull/22792): Backport UI tests for 1.7.7.2, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#22678](https://github.com/PrestaShop/PrestaShop/pull/22678): Fix nightly 1.7.7.x - 05/01/2021. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#22656](https://github.com/PrestaShop/PrestaShop/pull/22656): Delete UI upgrade test, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#22556](https://github.com/PrestaShop/PrestaShop/pull/22556): Fix nightly 1.7.7.x - 23/12/2020. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)


## Code changes in modules, themes & tools


### Changes in developer documentation
* [#846](https://github.com/PrestaShop/docs/pull/846): Removed duplicate in hook list. Thank you [@dpatou](https://github.com/dpatou)
* [#845](https://github.com/PrestaShop/docs/pull/845): Explain why config.xml should be added, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#844](https://github.com/PrestaShop/docs/pull/844): Update URL to UI kit demo. Thank you [@kpodemski](https://github.com/kpodemski)
* [#841](https://github.com/PrestaShop/docs/pull/841): how to access to service container in module. Thank you [@luigimassa](https://github.com/luigimassa)
* [#828](https://github.com/PrestaShop/docs/pull/828): Update infos about hooks actionAdminOrdersTrackingNumberUpdate, actionAdminMetaSave and actionAdminThemesControllerUpdate_optionsAfter, by [@matks](https://github.com/matks)
* [#549](https://github.com/PrestaShop/docs/pull/549): Update Order page doc. Thank you [@MatShir](https://github.com/MatShir)


### QA nightly results
* [#51](https://github.com/PrestaShop/QANightlyResults/pull/51): Merge develop into master, by [@atomiix](https://github.com/atomiix)
* [#50](https://github.com/PrestaShop/QANightlyResults/pull/50): Fix upgrade script, by [@atomiix](https://github.com/atomiix)
* [#49](https://github.com/PrestaShop/QANightlyResults/pull/49): Merge develop into master, by [@atomiix](https://github.com/atomiix)
* [#48](https://github.com/PrestaShop/QANightlyResults/pull/48): Use utf8 instead of utf8mb4, by [@atomiix](https://github.com/atomiix)
* [#47](https://github.com/PrestaShop/QANightlyResults/pull/47): Merge develop into master, by [@atomiix](https://github.com/atomiix)
* [#46](https://github.com/PrestaShop/QANightlyResults/pull/46): Bump to v3, by [@atomiix](https://github.com/atomiix)
* [#45](https://github.com/PrestaShop/QANightlyResults/pull/45): Merge develop into master, by [@atomiix](https://github.com/atomiix)
* [#44](https://github.com/PrestaShop/QANightlyResults/pull/44): Use platform instead of browser and allow CLI, by [@atomiix](https://github.com/atomiix)


### Wishlist block module
* [#95](https://github.com/PrestaShop/blockwishlist/pull/95): Change customization_required to customizable, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#94](https://github.com/PrestaShop/blockwishlist/pull/94): Update Parent tab to highlight Modules when on the configuration page, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Search Bar module
* [#27](https://github.com/PrestaShop/ps_searchbar/pull/27): Bump prestashop/php-dev-tools from 3.10 to 3.13. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#26](https://github.com/PrestaShop/ps_searchbar/pull/26): Bump version to 2.1.0, by [@Progi1984](https://github.com/Progi1984)
* [#24](https://github.com/PrestaShop/ps_searchbar/pull/24): Release 2.1.0, by [@Progi1984](https://github.com/Progi1984)


### PrestaShop contributors website
* [#51](https://github.com/PrestaShop/TopContributors/pull/51): Merge develop into integration, by [@Progi1984](https://github.com/Progi1984)
* [#50](https://github.com/PrestaShop/TopContributors/pull/50): Timeout increase. Thank you [@djodjo3](https://github.com/djodjo3)


### Customer reassurance block module
* [#107](https://github.com/PrestaShop/blockreassurance/pull/107): Bump webpack from 5.13.0 to 5.14.0. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#106](https://github.com/PrestaShop/blockreassurance/pull/106): Bump mini-css-extract-plugin from 1.3.3 to 1.3.4. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#105](https://github.com/PrestaShop/blockreassurance/pull/105): Bump webpack from 5.11.1 to 5.13.0. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#104](https://github.com/PrestaShop/blockreassurance/pull/104): Bump sass-loader from 10.1.0 to 10.1.1. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### Faceted search module
* [#306](https://github.com/PrestaShop/ps_facetedsearch/pull/306): Bump webpack from 5.13.0 to 5.14.0. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#305](https://github.com/PrestaShop/ps_facetedsearch/pull/305): Bump webpack from 5.12.3 to 5.13.0. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#304](https://github.com/PrestaShop/ps_facetedsearch/pull/304): Bump sass-loader from 10.1.0 to 10.1.1. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#303](https://github.com/PrestaShop/ps_facetedsearch/pull/303): Bump webpack from 5.11.1 to 5.12.3. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### User documentation landing page
* [#15](https://github.com/PrestaShop/user-documentation-landing/pull/15): chore(deps-dev): bump sass from 1.32.2 to 1.32.4. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#14](https://github.com/PrestaShop/user-documentation-landing/pull/14): chore(deps-dev): bump sass-loader from 10.1.0 to 10.1.1. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#13](https://github.com/PrestaShop/user-documentation-landing/pull/13): chore(deps-dev): bump @nuxtjs/pwa from 3.3.3 to 3.3.4. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#12](https://github.com/PrestaShop/user-documentation-landing/pull/12): chore(deps-dev): bump sass from 1.32.0 to 1.32.2. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### Docker images
* [#252](https://github.com/PrestaShop/docker/pull/252): Add 1.7.7.1 version, by [@PierreRambaud](https://github.com/PierreRambaud)


### Core Weekly Generator tool
* [#71](https://github.com/PrestaShop/core-weekly-generator/pull/71): More repos in coreteam.py, by [@matks](https://github.com/matks)


### Prestashop PHPStan extension
* [#3](https://github.com/PrestaShop/phpstan-prestashop/pull/3): Expand phpunit tests, by [@matks](https://github.com/matks)
* [#2](https://github.com/PrestaShop/phpstan-prestashop/pull/2): Add phpstan CI, by [@matks](https://github.com/matks)
* [#1](https://github.com/PrestaShop/phpstan-prestashop/pull/1): Improve README, by [@matks](https://github.com/matks)


### Email subscription module
* [#73](https://github.com/PrestaShop/ps_emailsubscription/pull/73): Spelling error. Thank you [@moncef-essid](https://github.com/moncef-essid)


### Best-selling products statistics module
* [#10](https://github.com/PrestaShop/statsbestproducts/pull/10): Use the good column for total. Thank you [@okom3pom](https://github.com/okom3pom)


### PrestaShop Specifications
* [#194](https://github.com/PrestaShop/prestashop-specs/pull/194): Create a checklist, by [@LouiseBonnard](https://github.com/LouiseBonnard)


### Best categories statistics module
* [#11](https://github.com/PrestaShop/statsbestcategories/pull/11): Use the good column for total. Thank you [@okom3pom](https://github.com/okom3pom)


### Category tree links module
* [#40](https://github.com/PrestaShop/ps_categorytree/pull/40): Release 2.0.1, by [@Progi1984](https://github.com/Progi1984)


## Where to start contributing?

What about fixing [an exception being thrown on Credit Slip Back-Office page](https://github.com/PrestaShop/PrestaShop/issues/22186) that happens when a credit slip is downloaded in debug mode? This is a bug reported one month ago, and it is one of our [good first issues](https://github.com/PrestaShop/PrestaShop/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22).

Good first issues are a list of all beginner-friendly improvements and bugs to fix in the project. You can read more about this label on [our article about it](https://build.prestashop.com/news/a-definition-of-the-good-first-issue-label).

<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@dpatou](https://github.com/dpatou), [@atomiix](https://github.com/atomiix), [@NeOMakinG](https://github.com/NeOMakinG), [@dependabot[bot]](https://github.com/apps/dependabot), [@Progi1984](https://github.com/Progi1984), [@jolelievre](https://github.com/jolelievre), [@kpodemski](https://github.com/kpodemski), [@Quetzacoalt91](https://github.com/Quetzacoalt91), [@djodjo3](https://github.com/djodjo3), [@PierreRambaud](https://github.com/PierreRambaud), [@matks](https://github.com/matks), [@nesrineabdmouleh](https://github.com/nesrineabdmouleh), [@boubkerbribri](https://github.com/boubkerbribri), [@PululuK](https://github.com/PululuK), [@Renrhaf](https://github.com/Renrhaf), [@jf-viguier](https://github.com/jf-viguier), [@SD1982](https://github.com/SD1982), [@Hlavtox](https://github.com/Hlavtox), [@sowbiba](https://github.com/sowbiba), [@moncef-essid](https://github.com/moncef-essid), [@luigimassa](https://github.com/luigimassa), [@okom3pom](https://github.com/okom3pom), [@LouiseBonnard](https://github.com/LouiseBonnard), [@zuk3975](https://github.com/zuk3975), [@IAmWebSA](https://github.com/IAmWebSA), [@JevgenijVisockij](https://github.com/JevgenijVisockij), [@MatShir](https://github.com/MatShir)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

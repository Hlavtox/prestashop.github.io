---
layout: post
aliases: ["/news/coreweekly-23-2020"]
slug: "coreweekly-23-2020"
title:  "PrestaShop Core Weekly - Week 23 of 2020"
subtitle: "An inside look at the PrestaShop codebase"
date:   2020-06-09
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 1st to Sunday 7th of June 2020.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)


## A quick update about PrestaShop's GitHub issues and pull requests:

- [104 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2020-06-01..2020-06-07) have been created in the project repositories;
- [75 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2020-06-01..2020-06-07), including [17 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2020-06-01..2020-06-07) on the core;
- [122 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2020-06-01..2020-06-07) in the project repositories;
- [94 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2020-06-01..2020-06-07), including [77 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2020-06-01..2020-06-07).



## Code changes in the 'develop' branch


### Core
* [#19539](https://github.com/PrestaShop/PrestaShop/pull/19539): Improve templates for GitHub, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#19528](https://github.com/PrestaShop/PrestaShop/pull/19528): Update version to 1.7.8.0, by [@Progi1984](https://github.com/Progi1984)
* [#19429](https://github.com/PrestaShop/PrestaShop/pull/19429): Refactor HookEvent to avoid DI mistake and clean LegacyHookSubscriber, by [@matks](https://github.com/matks)
* [#17439](https://github.com/PrestaShop/PrestaShop/pull/17439): Log Mail subject message correctly in case of alteration. Thank you [@davideapvd](https://github.com/davideapvd)


### Back office
* [#19598](https://github.com/PrestaShop/PrestaShop/pull/19598): Fix Product object model default values. Thank you [@zuk3975](https://github.com/zuk3975)
* [#19577](https://github.com/PrestaShop/PrestaShop/pull/19577): Refactor EditableProduct to ProductForEditing. Thank you [@zuk3975](https://github.com/zuk3975)
* [#19530](https://github.com/PrestaShop/PrestaShop/pull/19530): UpdateProductBasicInformationCommand. Thank you [@zuk3975](https://github.com/zuk3975)
* [#19529](https://github.com/PrestaShop/PrestaShop/pull/19529): Refacto AddProductCommand and introduce GetEditableProduct query, by [@jolelievre](https://github.com/jolelievre)
* [#19507](https://github.com/PrestaShop/PrestaShop/pull/19507): Update favicon alt + title name in BO. Thank you [@Klemart3D](https://github.com/Klemart3D)
* [#19407](https://github.com/PrestaShop/PrestaShop/pull/19407): UpdateProductDescriptionCommand. Thank you [@zuk3975](https://github.com/zuk3975)
* [#19299](https://github.com/PrestaShop/PrestaShop/pull/19299): Add basic structure for new Product startup, by [@jolelievre](https://github.com/jolelievre)
* [#18672](https://github.com/PrestaShop/PrestaShop/pull/18672): AddProductCommand. Thank you [@zuk3975](https://github.com/zuk3975)
* [#18322](https://github.com/PrestaShop/PrestaShop/pull/18322): Grid row delete confirmation modal - Catalog > Monitoring, by [@sowbiba](https://github.com/sowbiba)


### Front office
* [#19535](https://github.com/PrestaShop/PrestaShop/pull/19535): Remove unused code. Thank you [@idnovate](https://github.com/idnovate)
* [#19501](https://github.com/PrestaShop/PrestaShop/pull/19501): Check whether subcategories are empty before displaying them, by [@matks](https://github.com/matks)
* [#19438](https://github.com/PrestaShop/PrestaShop/pull/19438): Disable payment button if term checkbox is unchecked, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#19384](https://github.com/PrestaShop/PrestaShop/pull/19384): Replaced h2 title by h1 in the product listing of the catalog, by [@Progi1984](https://github.com/Progi1984)
* [#19116](https://github.com/PrestaShop/PrestaShop/pull/19116): Avoid showing 0 in Quantity field when the minimal quantity is 0. Thank you [@taoufiqaitali](https://github.com/taoufiqaitali)
* [#18562](https://github.com/PrestaShop/PrestaShop/pull/18562): Update node-sass version to support node 12 on classic theme, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#17423](https://github.com/PrestaShop/PrestaShop/pull/17423): Add a space before the dash separator when building the attributes names string. Thank you [@leup](https://github.com/leup)
* [#16828](https://github.com/PrestaShop/PrestaShop/pull/16828): Improve search performance for large shops. Thank you [@Darhazer](https://github.com/Darhazer)


### Web services
* [#19249](https://github.com/PrestaShop/PrestaShop/pull/19249): Fix illogical ternary condition for webservice filtering. Thank you [@DelecroixQuentin](https://github.com/DelecroixQuentin)


### Tests
* [#19588](https://github.com/PrestaShop/PrestaShop/pull/19588): Functional tests - Add submit delete modal to monitoring tests, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#19503](https://github.com/PrestaShop/PrestaShop/pull/19503): Functional tests - Fix unit price to check in product Settings tests. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#19500](https://github.com/PrestaShop/PrestaShop/pull/19500): Functional tests - Fix modal id in addresses test. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)


## Code changes in the '1.7.7.x' branch


### Core
* [#19556](https://github.com/PrestaShop/PrestaShop/pull/19556): Update modules (contactform/ps_imageslider/ps_sharebuttons/statspersonalinfos), by [@Progi1984](https://github.com/Progi1984)
* [#19016](https://github.com/PrestaShop/PrestaShop/pull/19016): Add mapping for Doctrine core entities on front environment, by [@jolelievre](https://github.com/jolelievre)


### Back office
* [#19546](https://github.com/PrestaShop/PrestaShop/pull/19546): Fix scrollbar on order page when adding product. Thank you [@antoinedamiron](https://github.com/antoinedamiron)
* [#19448](https://github.com/PrestaShop/PrestaShop/pull/19448): Fix AdminModulesController fatal error, by [@Matt75](https://github.com/Matt75)


### Front office
* [#19456](https://github.com/PrestaShop/PrestaShop/pull/19456): Fix voucher display for single customer - backport of 19443 to 1.7.7.x, by [@matks](https://github.com/matks)
* [#19437](https://github.com/PrestaShop/PrestaShop/pull/19437): Product cover in list, by [@jolelievre](https://github.com/jolelievre)
* [#19139](https://github.com/PrestaShop/PrestaShop/pull/19139): Do not use cache while checking if an order exists, by [@PierreRambaud](https://github.com/PierreRambaud)


### Tests
* [#19489](https://github.com/PrestaShop/PrestaShop/pull/19489): remove unused test, by [@SimonGrn](https://github.com/SimonGrn)


## Code changes in modules, themes & tools


### Wishlist block
* [#38](https://github.com/PrestaShop/blockwishlist/pull/38): Modify responsive of modals, manage attribute and quantity of product and more, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#35](https://github.com/PrestaShop/blockwishlist/pull/35): Toast, add fetch example, fix some things from last meeting, by [@NeOMakinG](https://github.com/NeOMakinG)


### Faceted search module
* [#171](https://github.com/PrestaShop/ps_facetedsearch/pull/171): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Customer data privacy block
* [#17](https://github.com/PrestaShop/ps_dataprivacy/pull/17): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Custom text
* [#39](https://github.com/PrestaShop/ps_customtext/pull/39): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Customer "Sign in" link
* [#19](https://github.com/PrestaShop/ps_customersignin/pull/19): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Customer account links
* [#24](https://github.com/PrestaShop/ps_customeraccountlinks/pull/24): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Cross-selling
* [#10](https://github.com/PrestaShop/ps_crossselling/pull/10): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Contact informations module
* [#33](https://github.com/PrestaShop/ps_contactinfo/pull/33): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Check payment
* [#31](https://github.com/PrestaShop/ps_checkpayment/pull/31): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Category tree links
* [#33](https://github.com/PrestaShop/ps_categorytree/pull/33): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Banner
* [#18](https://github.com/PrestaShop/ps_banner/pull/18): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Product Comments module
* [#56](https://github.com/PrestaShop/productcomments/pull/56): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Pages not found
* [#11](https://github.com/PrestaShop/pagesnotfound/pull/11): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Google Sitemap module
* [#136](https://github.com/PrestaShop/gsitemap/pull/136): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### NVD3 Charts
* [#9](https://github.com/PrestaShop/graphnvd3/pull/9): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Dashboard Trends
* [#27](https://github.com/PrestaShop/dashtrends/pull/27): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)
* [#26](https://github.com/PrestaShop/dashtrends/pull/26): Merge master into dev, by [@matks](https://github.com/matks)


### Dashboard Products
* [#23](https://github.com/PrestaShop/dashproducts/pull/23): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Dashboard Goals
* [#19](https://github.com/PrestaShop/dashgoals/pull/19): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Dashboard Activity module
* [#19](https://github.com/PrestaShop/dashactivity/pull/19): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)


### Contact Form
* [#42](https://github.com/PrestaShop/contactform/pull/42): Add CONTRIBUTORS file, by [@matks](https://github.com/matks)
* [#40](https://github.com/PrestaShop/contactform/pull/40): Release 4.2.0, by [@PierreRambaud](https://github.com/PierreRambaud)


### Catalog statistics
* [#9](https://github.com/PrestaShop/statscatalog/pull/9): Merge master into dev, by [@matks](https://github.com/matks)


### Search engine keywords
* [#9](https://github.com/PrestaShop/sekeywords/pull/9): Merge master into dev, by [@matks](https://github.com/matks)


### PS Cleaner module
* [#47](https://github.com/PrestaShop/pscleaner/pull/47): Add AFL LICENSE file, by [@matks](https://github.com/matks)


### Simple HTML table display
* [#9](https://github.com/PrestaShop/gridhtml/pull/9): Add AFL LICENSE file, by [@matks](https://github.com/matks)


### nightly-board
* [#34](https://github.com/PrestaShop/nightly-board/pull/34): Report page improvements, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#33](https://github.com/PrestaShop/nightly-board/pull/33): Add links to every td of index page, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#32](https://github.com/PrestaShop/nightly-board/pull/32): Responsive of new features, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#31](https://github.com/PrestaShop/nightly-board/pull/31): Add browsers, variance and filters on index page, by [@NeOMakinG](https://github.com/NeOMakinG)


### Link list
* [#88](https://github.com/PrestaShop/ps_linklist/pull/88): Provide useful data attributes into Link Widget hook list for puppeter tests, by [@Progi1984](https://github.com/Progi1984)
* [#86](https://github.com/PrestaShop/ps_linklist/pull/86): Fix install and uninstall processes that did not work in CLI environment, by [@jolelievre](https://github.com/jolelievre)


### QA nightly results
* [#42](https://github.com/PrestaShop/QANightlyResults/pull/42): update ternary choices, add filter by browser and campaign, by [@SimonGrn](https://github.com/SimonGrn)


### Changes in developer documentation
* [#555](https://github.com/PrestaShop/docs/pull/555): Adds warning about module console command, by [@Matt75](https://github.com/Matt75)
* [#552](https://github.com/PrestaShop/docs/pull/552): Use let/const instead of var, by [@matks](https://github.com/matks)
* [#548](https://github.com/PrestaShop/docs/pull/548): Add doc about modules & external services, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#538](https://github.com/PrestaShop/docs/pull/538): Improve the documentation for the case you need different node version, by [@NeOMakinG](https://github.com/NeOMakinG)


### Core Weekly Generator tool
* [#36](https://github.com/PrestaShop/core-weekly-generator/pull/36): Adding components to the list., by [@ttoine](https://github.com/ttoine)


### Image slider
* [#51](https://github.com/PrestaShop/ps_imageslider/pull/51): Release 3.1.0, by [@Progi1984](https://github.com/Progi1984)


### Registered customer information
* [#7](https://github.com/PrestaShop/statspersonalinfos/pull/7): Release 2.0.3, by [@Progi1984](https://github.com/Progi1984)


### Prestashop UI Kit
* [#94](https://github.com/PrestaShop/prestashop-ui-kit/pull/94): Bump jquery from 3.3.1 to 3.5.0. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### Cash on delivery
* [#10](https://github.com/PrestaShop/ps_cashondelivery/pull/10): FO: double customer object declaration. Thank you [@slupostrupek](https://github.com/slupostrupek)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@NeOMakinG](https://github.com/NeOMakinG), [@matks](https://github.com/matks), [@zuk3975](https://github.com/zuk3975), [@boubkerbribri](https://github.com/boubkerbribri), [@Progi1984](https://github.com/Progi1984), [@antoinedamiron](https://github.com/antoinedamiron), [@PierreRambaud](https://github.com/PierreRambaud), [@idnovate](https://github.com/idnovate), [@SimonGrn](https://github.com/SimonGrn), [@Matt75](https://github.com/Matt75), [@ttoine](https://github.com/ttoine), [@jolelievre](https://github.com/jolelievre), [@Klemart3D](https://github.com/Klemart3D), [@nesrineabdmouleh](https://github.com/nesrineabdmouleh), [@Quetzacoalt91](https://github.com/Quetzacoalt91), [@DelecroixQuentin](https://github.com/DelecroixQuentin), [@taoufiqaitali](https://github.com/taoufiqaitali), [@dependabot[bot]](https://github.com/apps/dependabot), [@sowbiba](https://github.com/sowbiba), [@davideapvd](https://github.com/davideapvd), [@leup](https://github.com/leup), [@Darhazer](https://github.com/Darhazer), [@slupostrupek](https://github.com/slupostrupek)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

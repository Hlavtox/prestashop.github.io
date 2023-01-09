---
layout: post
aliases: ["/news/coreweekly-week-36-2018"]
title:  "PrestaShop Core Weekly - Week 36 of 2018"
subtitle: "An inside look at the PrestaShop codebase"
date:   2018-09-14 16:50:00
authors: [ AntoineThomas ]
icon: icon-calendar
tags:
 - core-monthly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase during the last week, from Monday 3rd to Sunday 9th of September 2018.

![Core Weekly banner](/assets/images/2017/04/core_weekly_banner.jpg)


## General messages

This week, many people from the PrestaShop ecosystem came to meet the PrestaShop company at the Paris Retail Week. There was also a meeting at the Paris office, with French agencies and some of the top Addons contributors. That was great to share and discuss together about the present and the future of PrestaShop. Thank you to everyone who attended.

A quick reminder: please note that PrestaShop 1.7.5 code freeze will be on the 20th of september, and it's next week. After that date, no new wordings can be added, and only regression fixes will be merged into the release branch.

Module release:

* [Auto Upgrade 4.2.0](https://github.com/PrestaShop/autoupgrade/releases/tag/v4.2.0)


A quick update about GitHub issues: last week, [77 new issues](https://github.com/PrestaShop/PrestaShop/issues?utf8=%E2%9C%93&q=is:issue+created:2018-09-03..2018-09-09) issues have been opened in PrestaShop’s core repository, and [21 fixed issues](https://github.com/PrestaShop/PrestaShop/issues?utf8=%E2%9C%93&q=is:issue+label:fixed+closed:2018-09-03..2018-09-09) have been closed.

## Code changes in the 'develop' branch (for v1.7.5.0)

### Core

* [#9356](https://github.com/PrestaShop/PrestaShop/pull/9356): CO: Add new variable in product.php, to sort features in front. Thank you [@Lathanao](https://github.com/Lathanao)
* [#9402](https://github.com/PrestaShop/PrestaShop/pull/9402): Improve grid data providers. Thank you [@sarjon](https://github.com/sarjon)
* [#9460](https://github.com/PrestaShop/PrestaShop/pull/9460): Implementation of CQRS in SqlManager page. Thank you [@sarjon](https://github.com/sarjon)
* [#9475](https://github.com/PrestaShop/PrestaShop/pull/9475): Make title different from meta title on CMS for SEO purpose. Thank you [@Mreker](https://github.com/Mreker)
* [#10227](https://github.com/PrestaShop/PrestaShop/pull/10227): CO: Fixed error with inheritance. Thank you [@idnovate](https://github.com/idnovate)
* [#10233](https://github.com/PrestaShop/PrestaShop/pull/10233): HookDispatcher dispatchMultiple doesn't exists anymore, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#10241](https://github.com/PrestaShop/PrestaShop/pull/10241): Add Tactician command/query bus. Thank you [@sarjon](https://github.com/sarjon)
* [#10287](https://github.com/PrestaShop/PrestaShop/pull/10287): Fixed pre-commit hook script, by [@mickaelandrieu](https://github.com/mickaelandrieu)


### Back Office

* [#9324](https://github.com/PrestaShop/PrestaShop/pull/9324): Fixed the Show SQL query action, by [@mickaelandrieu](https://github.com/mickaelandrieu)
* [#9444](https://github.com/PrestaShop/PrestaShop/pull/9444): Add search engine result preview on product page, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#9453](https://github.com/PrestaShop/PrestaShop/pull/9453): Allow import entity to be preselected. Thank you [@sarjon](https://github.com/sarjon)
* [#9471](https://github.com/PrestaShop/PrestaShop/pull/9471): Build Back Office default theme using Webpack 4, by [@eternoendless](https://github.com/eternoendless)
* [#10135](https://github.com/PrestaShop/PrestaShop/pull/10135): [BOOM-6197] PDF documents unformatted. Thank you [@rdy4ever](https://github.com/rdy4ever)
* [#10202](https://github.com/PrestaShop/PrestaShop/pull/10202): Fix 'edit specific price' modal behavior bugs and display, by [@matks](https://github.com/matks)
* [#10208](https://github.com/PrestaShop/PrestaShop/pull/10208): Migration of Advanced Parameters -> Webservice -> listing. Thank you [@tomas862](https://github.com/tomas862)
* [#10219](https://github.com/PrestaShop/PrestaShop/pull/10219): Minor grid improvements. Thank you [@sarjon](https://github.com/sarjon)
* [#10221](https://github.com/PrestaShop/PrestaShop/pull/10221): BO \| Product Page: fix visual glitches in categories filter. Thank you [@CaptainYouz](https://github.com/CaptainYouz)
* [#10223](https://github.com/PrestaShop/PrestaShop/pull/10223): Fixed DB backup page, by [@mickaelandrieu](https://github.com/mickaelandrieu)
* [#10242](https://github.com/PrestaShop/PrestaShop/pull/10242): BO: Fix wrong translations. Thank you [@ramtin2025](https://github.com/ramtin2025)
* [#10260](https://github.com/PrestaShop/PrestaShop/pull/10260): Fix help sidebar not working in the Stock page. Thank you [@CaptainYouz](https://github.com/CaptainYouz)
* [#10281](https://github.com/PrestaShop/PrestaShop/pull/10281): Fixed minor issues on Logs Grid page, by [@mickaelandrieu](https://github.com/mickaelandrieu)
* [#10302](https://github.com/PrestaShop/PrestaShop/pull/10302): Images aren't displayed in combinations with new products, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#10322](https://github.com/PrestaShop/PrestaShop/pull/10322): Wrong variable name , by [@PierreRambaud](https://github.com/PierreRambaud)
* [#10326](https://github.com/PrestaShop/PrestaShop/pull/10326): Manage getAdminBaseLink in LegacyContext::getAdminLink, by [@jolelievre](https://github.com/jolelievre)


### Front Office

* [#9362](https://github.com/PrestaShop/PrestaShop/pull/9362): [FO] Add breadcrumb to the contact page. Thank you [@SebBareyre](https://github.com/SebBareyre)
* [#9459](https://github.com/PrestaShop/PrestaShop/pull/9459): Show the category block in the list page on first page only, by [@jolelievre](https://github.com/jolelievre)
* [#9472](https://github.com/PrestaShop/PrestaShop/pull/9472): Modify category pagination for SEO purposes, by [@jolelievre](https://github.com/jolelievre)
* [#10254](https://github.com/PrestaShop/PrestaShop/pull/10254): Fix getTotalWeight Notice. Thank you [@duGuillaume](https://github.com/duGuillaume)
* [#10279](https://github.com/PrestaShop/PrestaShop/pull/10279): Check minimal quantity. Thank you [@sadlyblue](https://github.com/sadlyblue)


### Tests

* [#10249](https://github.com/PrestaShop/PrestaShop/pull/10249): Use PHP_BINARY while using createTestDb, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#10276](https://github.com/PrestaShop/PrestaShop/pull/10276): Run PHP CS Fixer, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


## Code changes in modules, themes & tools

### Auto Upgrade

* [#152](https://github.com/PrestaShop/autoupgrade/pull/152): Fix undefined trans in Workspace class, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#155](https://github.com/PrestaShop/autoupgrade/pull/155): Deploying v4.1.1 of 1-click upgrade, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#156](https://github.com/PrestaShop/autoupgrade/pull/156): Bump to v4.1.1, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#157](https://github.com/PrestaShop/autoupgrade/pull/157): Check cURL without PS core, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#160](https://github.com/PrestaShop/autoupgrade/pull/160): Fix ignored files outside shop folder, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#161](https://github.com/PrestaShop/autoupgrade/pull/161): Update Readme.md, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#162](https://github.com/PrestaShop/autoupgrade/pull/162): Apply Cs fixer, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#164](https://github.com/PrestaShop/autoupgrade/pull/164): Revert "Fix ignored files outside shop folder", by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Mail alerts

* [#36](https://github.com/PrestaShop/mailalerts/pull/36): Apply Cs fixes, by [@PierreRambaud](https://github.com/PierreRambaud)


### Faceted navigation block

* [#38](https://github.com/PrestaShop/ps_facetedsearch/pull/38): Append composer autoloader in config, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#41](https://github.com/PrestaShop/ps_facetedsearch/pull/41): Deploying v2.2.0, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#42](https://github.com/PrestaShop/ps_facetedsearch/pull/42): Bump version to 2.2.0, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Products in the same category

* [#2](https://github.com/PrestaShop/ps_categoryproducts/pull/2): Make more precise variable type check, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#3](https://github.com/PrestaShop/ps_categoryproducts/pull/3): Bump version to 1.0.3, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#4](https://github.com/PrestaShop/ps_categoryproducts/pull/4): Deploying version 1.0.3, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### MBO

* [#29](https://github.com/PrestaShop/ps_mbo/pull/29): Loading time of carriers & payment pages #23. Thank you [@MrBaiame](https://github.com/MrBaiame)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: @CaptainYouz, @duGuillaume, @idnovate, @Lathanao, @MrBaiame, @Mreker, @ramtin2025, @rdy4ever, @sadlyblue, @sarjon, @SebBareyre, @tomas862!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

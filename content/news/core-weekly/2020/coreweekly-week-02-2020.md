---
layout: post
aliases: ["/news/coreweekly-week-02-2020"]
title:  "PrestaShop Core Weekly - Week 2 of 2020"
subtitle: "An inside look at the PrestaShop codebase"
date:   2020-01-13
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 6th to Sunday 12th of January 2020.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)

## General messages

Dear developers,

If you have not read it yet, please check [our statement about a critical security vulnerability in PrestaShop Modules](https://build.prestashop.com/news/critical-security-vulnerability-in-prestashop-modules/).

Also activity on prestashop is resuming back to normal now with both contributions and reviews coming back stronger. The team is mainly focused on [finishing the remaining 1.7.6.x issues](https://github.com/PrestaShop/PrestaShop/projects/4) in order to be able to release 1.7.6.3 soon.

## A quick update about PrestaShop's GitHub issues and pull requests:

- [58 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2020-01-06..2020-01-12) have been created in the project repositories;
- [47 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2020-01-06..2020-01-12), including [18 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2020-01-06..2020-01-12) on the core;
- [67 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2020-01-06..2020-01-12) in the project repositories;
- [92 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2020-01-06..2020-01-12), including [85 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2020-01-06..2020-01-12).


## Code changes in the 'develop' branch


### Core
* [#17067](https://github.com/PrestaShop/PrestaShop/pull/17067): Fix phpdoc on Category constructor. Thank you [@zalexki](https://github.com/zalexki)
* [#17048](https://github.com/PrestaShop/PrestaShop/pull/17048): Update nginx configuration, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#16714](https://github.com/PrestaShop/PrestaShop/pull/16714): Update composer.json requirements. Thank you [@gavinkalika](https://github.com/gavinkalika)
* [#8770](https://github.com/PrestaShop/PrestaShop/pull/8770): CO: remove file 'fileType' when deleting images. Thank you [@marekhanus](https://github.com/marekhanus)


### Back office
* [#17079](https://github.com/PrestaShop/PrestaShop/pull/17079): Improve modal object without using this. Thank you [@NeOMakinG](https://github.com/NeOMakinG)
* [#16883](https://github.com/PrestaShop/PrestaShop/pull/16883): Fixed filtering for date in Back Office / Logs. Thank you [@PrestaworksNiklas](https://github.com/PrestaworksNiklas)
* [#16860](https://github.com/PrestaShop/PrestaShop/pull/16860): Fix United Kingdom VAT issue for all EU countries. Thank you [@jf-viguier](https://github.com/jf-viguier)
* [#16820](https://github.com/PrestaShop/PrestaShop/pull/16820): Enable confirm modal for catalog > files listing for bulk delete action, by [@matks](https://github.com/matks)
* [#16765](https://github.com/PrestaShop/PrestaShop/pull/16765): Fix recursive check of updated files. Thank you [@Darhazer](https://github.com/Darhazer)
* [#16668](https://github.com/PrestaShop/PrestaShop/pull/16668): Integrate a Vue component to manage Currency customization in the BO, by [@jolelievre](https://github.com/jolelievre)
* [#16207](https://github.com/PrestaShop/PrestaShop/pull/16207): Migrate summary block of BO create order page. Thank you [@zuk3975](https://github.com/zuk3975)
* [#16150](https://github.com/PrestaShop/PrestaShop/pull/16150): Migrate order product management. Thank you [@sarjon](https://github.com/sarjon)
* [#15300](https://github.com/PrestaShop/PrestaShop/pull/15300): Migration for Sell > Customers > Addresses create/edit forms. Thank you [@RaimondasSapola](https://github.com/RaimondasSapola)


### Front office
* [#17005](https://github.com/PrestaShop/PrestaShop/pull/17005): Adding default "Select" when sort not up in FO is selected on category page. Thank you [@NeOMakinG](https://github.com/NeOMakinG)
* [#16724](https://github.com/PrestaShop/PrestaShop/pull/16724): Fix multiple cart rules calculation. Thank you [@atomiix](https://github.com/atomiix)
* [#16574](https://github.com/PrestaShop/PrestaShop/pull/16574): Fix product cannot be deleted from cart IF another customization is made and not added to cart yet. Thank you [@Hlavtox](https://github.com/Hlavtox)
* [#16520](https://github.com/PrestaShop/PrestaShop/pull/16520): Fixing contact layout not working at all. Thank you [@NeOMakinG](https://github.com/NeOMakinG)
* [#15284](https://github.com/PrestaShop/PrestaShop/pull/15284): Color and texture consistent when both are set. Thank you [@davidglezz](https://github.com/davidglezz)
* [#15277](https://github.com/PrestaShop/PrestaShop/pull/15277): Combine two equal adjacent selectors. Thank you [@davidglezz](https://github.com/davidglezz)


### Tests
* [#17094](https://github.com/PrestaShop/PrestaShop/pull/17094): Add twig lint check and move bash script from tests-legacy to tests, by [@matks](https://github.com/matks)
* [#17092](https://github.com/PrestaShop/PrestaShop/pull/17092): Functional tests - Fix other options test. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#17091](https://github.com/PrestaShop/PrestaShop/pull/17091): Functional tests - Fix Crud language test, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#17084](https://github.com/PrestaShop/PrestaShop/pull/17084): Functional tests - Fix error in the test Enable/Disable invoices. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#17076](https://github.com/PrestaShop/PrestaShop/pull/17076): Tests - Fix dockerfile for puppeteer, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#17066](https://github.com/PrestaShop/PrestaShop/pull/17066): Functional tests - Update confirm delete files method, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#17061](https://github.com/PrestaShop/PrestaShop/pull/17061): Functional tests - Add base page for localization, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#17060](https://github.com/PrestaShop/PrestaShop/pull/17060): Functional tests - Filter addresses table. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#17052](https://github.com/PrestaShop/PrestaShop/pull/17052): Functional tests - Add new test 'Crud language test', by [@boubkerbribri](https://github.com/boubkerbribri)
* [#17047](https://github.com/PrestaShop/PrestaShop/pull/17047): Functional tests - Enable disable image in delivery slip file. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#17041](https://github.com/PrestaShop/PrestaShop/pull/17041): Functional tests - Fix tests brands and skip test Create unofficial currencies, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#17029](https://github.com/PrestaShop/PrestaShop/pull/17029): Functional Tests - Enable/Disable shop. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#17027](https://github.com/PrestaShop/PrestaShop/pull/17027): Functional tests -  add test 'Filter modules by status', by [@boubkerbribri](https://github.com/boubkerbribri)
* [#17013](https://github.com/PrestaShop/PrestaShop/pull/17013): Functional tests - Separate tests team employees and profiles, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#17009](https://github.com/PrestaShop/PrestaShop/pull/17009): Functional tests - add test 'Preview Email Themes', by [@boubkerbribri](https://github.com/boubkerbribri)
* [#16998](https://github.com/PrestaShop/PrestaShop/pull/16998): Fix #16997 - assertion of first/classic theme from unsorted list. Thank you [@mvorisek](https://github.com/mvorisek)
* [#16967](https://github.com/PrestaShop/PrestaShop/pull/16967): Functional Tests - Add number verification for delivery slip file. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#16963](https://github.com/PrestaShop/PrestaShop/pull/16963): Functional tests - add test 'filter languages', by [@boubkerbribri](https://github.com/boubkerbribri)
* [#16809](https://github.com/PrestaShop/PrestaShop/pull/16809): Fix date parsing in tests when TZ is changed to non-UTC during tests. Thank you [@mvorisek](https://github.com/mvorisek)
* [#16632](https://github.com/PrestaShop/PrestaShop/pull/16632): Replace deprecated "create_function". Thank you [@mvorisek](https://github.com/mvorisek)


## Code changes in the '1.7.6.x' branch (for 1.7.6.3)


### Core
* [#17050](https://github.com/PrestaShop/PrestaShop/pull/17050): Quick access error when having a wrong url, by [@PierreRambaud](https://github.com/PierreRambaud)


### Back office
* [#17087](https://github.com/PrestaShop/PrestaShop/pull/17087): Define alert message when error are found in Category Form, by [@Progi1984](https://github.com/Progi1984)
* [#17071](https://github.com/PrestaShop/PrestaShop/pull/17071): Fix recursive check of updated files - backport of #16765, by [@matks](https://github.com/matks)
* [#17065](https://github.com/PrestaShop/PrestaShop/pull/17065): Fix encoding on product name in viewed product, by [@Progi1984](https://github.com/Progi1984)
* [#17036](https://github.com/PrestaShop/PrestaShop/pull/17036): Protect modules vendor folder on install/upgrade/enable, by [@jolelievre](https://github.com/jolelievre)
* [#16742](https://github.com/PrestaShop/PrestaShop/pull/16742): Can't export data more than filters limits, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#16696](https://github.com/PrestaShop/PrestaShop/pull/16696): Fix email theme permission. Thank you [@atomiix](https://github.com/atomiix)


### Front office
* [#17030](https://github.com/PrestaShop/PrestaShop/pull/17030): Ignore rtl assets and remove _rtl.css files. Thank you [@NeOMakinG](https://github.com/NeOMakinG)
* [#16852](https://github.com/PrestaShop/PrestaShop/pull/16852): Fix a bug where changing quantity on product quickview adds products tags on ever products. Thank you [@NeOMakinG](https://github.com/NeOMakinG)


### Web services
* [#17069](https://github.com/PrestaShop/PrestaShop/pull/17069): Fix Currency i18n fields issue in webservice. Thank you [@atomiix](https://github.com/atomiix)


## Code changes in modules, themes & tools


### QA nightly results
* [#16](https://github.com/PrestaShop/QANightlyResults/pull/16): Add support for pending colors, by [@SimonGrn](https://github.com/SimonGrn)
* [#15](https://github.com/PrestaShop/QANightlyResults/pull/15): add possibility to check pending tests, by [@SimonGrn](https://github.com/SimonGrn)


### Changes in developer documentation
* [#439](https://github.com/PrestaShop/docs/pull/439): Add validation rule about altering other modules, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#438](https://github.com/PrestaShop/docs/pull/438): Update links to README for Puppeteer tests, by [@SimonGrn](https://github.com/SimonGrn)
* [#436](https://github.com/PrestaShop/docs/pull/436): Add mbstring as required, by [@eternoendless](https://github.com/eternoendless)
* [#435](https://github.com/PrestaShop/docs/pull/435): Update alert block for composer dependencies, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#434](https://github.com/PrestaShop/docs/pull/434): Add benchmark informations from white paper, by [@tomlev](https://github.com/tomlev)
* [#433](https://github.com/PrestaShop/docs/pull/433): Create dedicated page for validation checklist, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#408](https://github.com/PrestaShop/docs/pull/408): Update _index.md. Thank you [@guirou62](https://github.com/guirou62)
* [#381](https://github.com/PrestaShop/docs/pull/381): Add documentation for updatedProduct. Thank you [@saturnxxi](https://github.com/saturnxxi)
* [#293](https://github.com/PrestaShop/docs/pull/293): Update installation instructions. Thank you [@LocalHeroPro](https://github.com/LocalHeroPro)


### Gamification module
* [#71](https://github.com/PrestaShop/gamification/pull/71): Merge master into dev, by [@matks](https://github.com/matks)


### Faceted search module
* [#153](https://github.com/PrestaShop/ps_facetedsearch/pull/153): Merge master into dev, by [@matks](https://github.com/matks)
* [#152](https://github.com/PrestaShop/ps_facetedsearch/pull/152): Apply php-cs-fixer, by [@matks](https://github.com/matks)


### Auto Upgrade module
* [#346](https://github.com/PrestaShop/autoupgrade/pull/346): Fix codestyle and merge master into dev, by [@matks](https://github.com/matks)
* [#344](https://github.com/PrestaShop/autoupgrade/pull/344): Update license headers & add all index.php, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Share buttons module
* [#29](https://github.com/PrestaShop/ps_sharebuttons/pull/29): Remove Google+. Thank you [@micka-fdz](https://github.com/micka-fdz)


### Product Comments module
* [#47](https://github.com/PrestaShop/productcomments/pull/47): Correct position on modal comment mobile. Thank you [@NeOMakinG](https://github.com/NeOMakinG)


### Prestashop UI Kit
* [#83](https://github.com/PrestaShop/prestashop-ui-kit/pull/83): Add help-box and improve popover component. Thank you [@NeOMakinG](https://github.com/NeOMakinG)
* [#82](https://github.com/PrestaShop/prestashop-ui-kit/pull/82): Improve Breadcrumbs. Thank you [@NeOMakinG](https://github.com/NeOMakinG)
* [#80](https://github.com/PrestaShop/prestashop-ui-kit/pull/80): Modal improvements (box shadow, border-radius, paddings..). Thank you [@NeOMakinG](https://github.com/NeOMakinG)
* [#78](https://github.com/PrestaShop/prestashop-ui-kit/pull/78): Change border color and adding margin to checkbox material element. Thank you [@NeOMakinG](https://github.com/NeOMakinG)
* [#75](https://github.com/PrestaShop/prestashop-ui-kit/pull/75): Add toast modifier to alert component. Thank you [@NeOMakinG](https://github.com/NeOMakinG)
* [#70](https://github.com/PrestaShop/prestashop-ui-kit/pull/70): Adjust colors, sizes of buttons group and buttons group dropdown. Thank you [@NeOMakinG](https://github.com/NeOMakinG)
* [#69](https://github.com/PrestaShop/prestashop-ui-kit/pull/69): Adjust colors, sizes or primary buttons and icons. Thank you [@NeOMakinG](https://github.com/NeOMakinG)
* [#68](https://github.com/PrestaShop/prestashop-ui-kit/pull/68): Bump mixin-deep from 1.3.1 to 1.3.2. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### Main menu module
* [#28](https://github.com/PrestaShop/ps_mainmenu/pull/28): Fix updating custom links + fix for relative links. Thank you [@sharkooon](https://github.com/sharkooon)


### Email Alerts module
* [#29](https://github.com/PrestaShop/ps_emailalerts/pull/29): Fix total tax when using discounts. Thank you [@Hlavtox](https://github.com/Hlavtox)


### Email subscription module
* [#47](https://github.com/PrestaShop/ps_emailsubscription/pull/47): Fix issue where html tags from ps_emailsubscription module would be escaped and not interpreted as HTML. Thank you [@NeOMakinG](https://github.com/NeOMakinG)


### GSitemap module
* [#127](https://github.com/PrestaShop/gsitemap/pull/127): Fix failure when generating sitemap with >25000 links. Thank you [@DavidBoone](https://github.com/DavidBoone)


### Search bar module
* [#12](https://github.com/PrestaShop/ps_searchbar/pull/12): New searchbar design. Thank you [@atomiix](https://github.com/atomiix)


### New products module
* [#2](https://github.com/PrestaShop/ps_newproducts/pull/2): products visible in catalog mode. Thank you [@Oksydan](https://github.com/Oksydan)


### Dash Activity module
* [#16](https://github.com/PrestaShop/dashactivity/pull/16): Remove addjquery, by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#15](https://github.com/PrestaShop/dashactivity/pull/15): Fix online visitor values. Thank you [@ckubitza](https://github.com/ckubitza)


### Socialfollow module
* [#13](https://github.com/PrestaShop/ps_socialfollow/pull/13): No more Google+. Thank you [@kpodemski](https://github.com/kpodemski)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@matks](https://github.com/matks), [@nesrineabdmouleh](https://github.com/nesrineabdmouleh), [@boubkerbribri](https://github.com/boubkerbribri), [@Progi1984](https://github.com/Progi1984), [@SimonGrn](https://github.com/SimonGrn), [@NeOMakinG](https://github.com/NeOMakinG), [@Quetzacoalt91](https://github.com/Quetzacoalt91), [@atomiix](https://github.com/atomiix), [@zalexki](https://github.com/zalexki), [@PierreRambaud](https://github.com/PierreRambaud), [@eternoendless](https://github.com/eternoendless), [@jolelievre](https://github.com/jolelievre), [@micka-fdz](https://github.com/micka-fdz), [@tomlev](https://github.com/tomlev), [@mvorisek](https://github.com/mvorisek), [@PrestaworksNiklas](https://github.com/PrestaworksNiklas), [@jf-viguier](https://github.com/jf-viguier), [@Darhazer](https://github.com/Darhazer), [@gavinkalika](https://github.com/gavinkalika), [@sharkooon](https://github.com/sharkooon), [@Hlavtox](https://github.com/Hlavtox), [@guirou62](https://github.com/guirou62), [@DavidBoone](https://github.com/DavidBoone), [@dependabot[bot]](https://github.com/apps/dependabot), [@zuk3975](https://github.com/zuk3975), [@sarjon](https://github.com/sarjon), [@saturnxxi](https://github.com/saturnxxi), [@Oksydan](https://github.com/Oksydan), [@matthieu-rolland](https://github.com/matthieu-rolland), [@RaimondasSapola](https://github.com/RaimondasSapola), [@davidglezz](https://github.com/davidglezz), [@ckubitza](https://github.com/ckubitza), [@LocalHeroPro](https://github.com/LocalHeroPro), [@kpodemski](https://github.com/kpodemski), [@marekhanus](https://github.com/marekhanus)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

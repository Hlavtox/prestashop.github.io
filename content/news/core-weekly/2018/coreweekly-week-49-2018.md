---
layout: post
aliases: ["/news/coreweekly-week-49-2018"]
title:  "PrestaShop Core Weekly - Week 49 of 2018"
subtitle: "An inside look at the PrestaShop codebase"
date:   2018-12-20 17:30:00
authors: [ AntoineThomas ]
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase during the last week, from Monday 03rd to Sunday 09th of December 2018.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)


## General messages

Dear developers,

We are one day before the week-end and the Holidays season. Jingle bells, Jingle bells :-)

 At PrestaShop, we would like to thank the most important contributors of the year, and we have already some goodies in stock. What do you think? What kind of things would you like and be proud to wear or to use? Please comment this article or get in touch with us.


## A quick update about GitHub issues

Last week, [65 new issues](https://github.com/PrestaShop/PrestaShop/issues?utf8=%E2%9C%93&q=is:issue+created:2018-11-03..2018-11-09) have been created in PrestaShop's core repository, and [16 fixed issues](https://github.com/PrestaShop/PrestaShop/issues?utf8=%E2%9C%93&q=is:issue+label:fixed+closed:2018-11-03..2018-11-09) have been closed.

## Code changes in the 'develop' branch (for v1.7.6.0)

### Core

* [#9132](https://github.com/PrestaShop/PrestaShop/pull/9132): extra field hook added on customer address form. Thank you [@PeeyushAgrawalWebkul](https://github.com/PeeyushAgrawalWebkul)
* [#10197](https://github.com/PrestaShop/PrestaShop/pull/10197): Added a schema generator, by [@mickaelandrieu](https://github.com/mickaelandrieu)
* [#11214](https://github.com/PrestaShop/PrestaShop/pull/11214): Handles bad address usecase for Carrier Tax Rate, by [@matks](https://github.com/matks)
* [#11246](https://github.com/PrestaShop/PrestaShop/pull/11246): Fix 10962: Replace deprecated library PhpExcel by PhpSpreadsheet. Thank you [@MartinFinkenflugel](https://github.com/MartinFinkenflugel)
* [#11249](https://github.com/PrestaShop/PrestaShop/pull/11249): Fix declaration of method arguments. Thank you [@Seleda](https://github.com/Seleda)
* [#11301](https://github.com/PrestaShop/PrestaShop/pull/11301): Merge 1.7.5.x in develop, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Back office

* [#10904](https://github.com/PrestaShop/PrestaShop/pull/10904): Fix date filtering in AdminSpecificPriceRuleController. Thank you [@Matt75](https://github.com/Matt75)
* [#11049](https://github.com/PrestaShop/PrestaShop/pull/11049): Add Helper Card to Employees page. Thank you [@sarjon](https://github.com/sarjon)
* [#11095](https://github.com/PrestaShop/PrestaShop/pull/11095): Introduces grid design update regarding grid wheel icon position and dropdown toggle icon modification. Thank you [@tomas862](https://github.com/tomas862)
* [#11179](https://github.com/PrestaShop/PrestaShop/pull/11179): Fix sorting issue in the webservice page, by [@khouloudbelguith](https://github.com/khouloudbelguith)
* [#11266](https://github.com/PrestaShop/PrestaShop/pull/11266): $this->fetch() can return content in BO context, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Front office

* [#11133](https://github.com/PrestaShop/PrestaShop/pull/11133): Removed inline-style of color in demo product desciption of "Hummingbi…. Thank you [@dineshbadrukhiya](https://github.com/dineshbadrukhiya)


### Tests

* [#11184](https://github.com/PrestaShop/PrestaShop/pull/11184): Advanced localization. Thank you [@ansar21mallouli](https://github.com/ansar21mallouli)
* [#11237](https://github.com/PrestaShop/PrestaShop/pull/11237): Improved survival tests, by [@mickaelandrieu](https://github.com/mickaelandrieu)
* [#11306](https://github.com/PrestaShop/PrestaShop/pull/11306): Fix linter jobs of Travis, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


## Code changes in the '1.7.5.x' branch (for v1.7.5.0)

### Core

* [#10845](https://github.com/PrestaShop/PrestaShop/pull/10845): Minor services naming fix. Thank you [@sarjon](https://github.com/sarjon)
* [#11058](https://github.com/PrestaShop/PrestaShop/pull/11058): Add Hindi, Mexican & Bosnian languages, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#11070](https://github.com/PrestaShop/PrestaShop/pull/11070): Feature/module manager categories, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#11300](https://github.com/PrestaShop/PrestaShop/pull/11300): Fix error on tab unregistration when handled by the module, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Back office

* [#10956](https://github.com/PrestaShop/PrestaShop/pull/10956): Fix product features, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#11147](https://github.com/PrestaShop/PrestaShop/pull/11147): PositionColummn UI/UX modifications, by [@jolelievre](https://github.com/jolelievre)
* [#11287](https://github.com/PrestaShop/PrestaShop/pull/11287): Fix filemanager security breaches, by [@jolelievre](https://github.com/jolelievre)
* [#11312](https://github.com/PrestaShop/PrestaShop/pull/11312): Prevent short description limit to be set at 0, by [@jolelievre](https://github.com/jolelievre)


### Front office

* [#11215](https://github.com/PrestaShop/PrestaShop/pull/11215): Fix 11211: Removing inline-style of color in test-data. Thank you [@dineshbadrukhiya](https://github.com/dineshbadrukhiya)
* [#11261](https://github.com/PrestaShop/PrestaShop/pull/11261): Fixed inconsistent locale in Front Office, by [@mickaelandrieu](https://github.com/mickaelandrieu)


## Code changes in the '1.7.4.x' branch (for v1.7.4.4)

### Core

* [#9316](https://github.com/PrestaShop/PrestaShop/pull/9316): Fix Cart::autoAddToCart using undefined customer when called from BO. Thank you [@prestamodule](https://github.com/prestamodule)


### Back office

* [#11228](https://github.com/PrestaShop/PrestaShop/pull/11228): Avoid warning in WebServiceRequest. Thank you [@AJenbo](https://github.com/AJenbo)
* [#11285](https://github.com/PrestaShop/PrestaShop/pull/11285): Fix filemanager security breaches, by [@jolelievre](https://github.com/jolelievre)


## Code changes in the '1.6.1.x' branch (for v1.6.1.24)

### Core

* [#11288](https://github.com/PrestaShop/PrestaShop/pull/11288): Update Changelog and Contributors, by [@jolelievre](https://github.com/jolelievre)


### Back office

* [#11286](https://github.com/PrestaShop/PrestaShop/pull/11286): Fix filemanager security breaches, by [@jolelievre](https://github.com/jolelievre)


## Code changes in modules, themes & tools

### Google Sitemap

* [#60](https://github.com/PrestaShop/gsitemap/pull/60): Fix wrong use of protocol. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#61](https://github.com/PrestaShop/gsitemap/pull/61): Remove the home category from the sitemap. Thank you [@MathiasReker](https://github.com/MathiasReker)


### Auto Upgrade

* [#187](https://github.com/PrestaShop/autoupgrade/pull/187): Fix auto reload when updating the config, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#188](https://github.com/PrestaShop/autoupgrade/pull/188): Deploying v4.4.1 of the 1-click upgrade module, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#189](https://github.com/PrestaShop/autoupgrade/pull/189): Improve installation instructions on README file. Thank you [@efernandesng](https://github.com/efernandesng)


### Link list

* [#48](https://github.com/PrestaShop/ps_linklist/pull/48): Refactor ps_linklist module using 1.7 improvements, by [@jolelievre](https://github.com/jolelievre)
* [#51](https://github.com/PrestaShop/ps_linklist/pull/51): Update major version, by [@jolelievre](https://github.com/jolelievre)


### MBO

* [#61](https://github.com/PrestaShop/ps_mbo/pull/61): Avoid doing admin tasks in the module constructor, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#62](https://github.com/PrestaShop/ps_mbo/pull/62): Remove unused category object from template, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#63](https://github.com/PrestaShop/ps_mbo/pull/63):  1.0.9, by [@MrBaiame](https://github.com/MrBaiame)
* [#65](https://github.com/PrestaShop/ps_mbo/pull/65): fix configure link, by [@MrBaiame](https://github.com/MrBaiame)


### Simplify Commerce Payment

* [#13](https://github.com/PrestaShop/simplifycommerce/pull/13): Removing pricing and sign-up information on the landing page. Thank you [@e079852](https://github.com/e079852)


### PrestaShop cleaner

* [#16](https://github.com/PrestaShop/pscleaner/pull/16): Delete CHANGELOG.txt. Thank you [@prestamodule](https://github.com/prestamodule)


### Translation tools bundle

* [#52](https://github.com/PrestaShop/TranslationToolsBundle/pull/52): Improve extraction of wordings from Smarty templates, by [@eternoendless](https://github.com/eternoendless)
* [#53](https://github.com/PrestaShop/TranslationToolsBundle/pull/53): Handle read Xliff metadata when dumping files, by [@eternoendless](https://github.com/eternoendless)
* [#54](https://github.com/PrestaShop/TranslationToolsBundle/pull/54): Sort file elements in exported Xliff, by [@eternoendless](https://github.com/eternoendless)


### Check payment

* [#18](https://github.com/PrestaShop/ps_checkpayment/pull/18): Fix non-existent image src in admin. Thank you [@the-ge](https://github.com/the-ge)
* [#19](https://github.com/PrestaShop/ps_checkpayment/pull/19): Bump version, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#20](https://github.com/PrestaShop/ps_checkpayment/pull/20): Deploying v2.0.4 of ps_checkpayment, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


## Changes in Documentation

* [#158](https://github.com/PrestaShop/docs/pull/158): Update Routing doc to explain _legacy_link, by [@jolelievre](https://github.com/jolelievre)
* [#160](https://github.com/PrestaShop/docs/pull/160): Correct a few mistakes in the legacy link doc, by [@jolelievre](https://github.com/jolelievre)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: @AJenbo, @ansar21mallouli, @e079852, @efernandesng, @dineshbadrukhiya, @MartinFinkenflugel, @MathiasReker, @Matt75, @MrBaiame, @PeeyushAgrawalWebkul, @prestamodule, @sarjon, @Seleda, @the-ge, @tomas862!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

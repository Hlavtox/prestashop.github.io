---
layout: post
aliases: ["/news/coreweekly-week-35-2018"]
title:  "PrestaShop Core Weekly - Week 35 of 2018"
subtitle: "An inside look at the PrestaShop codebase"
date:   2018-09-06 16:30:00
authors: [ AntoineThomas ]
icon: icon-calendar
tags:
 - core-monthly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase during the last week, from Monday 27th of August to Sunday 2nd of September 2018.

![Core Weekly banner](/assets/images/2017/04/core_weekly_banner.jpg)


## General messages

Dear developers, alas, the end of summer is here. However, the good news is that it's time to get back to work and to contribute to PrestaShop again ;-)

This week, three module have been updated:

* [Auto upgrade 4.1.1](https://github.com/PrestaShop/autoupgrade/releases/tag/v4.1.1)
* [Products in the same category 1.0.3](https://github.com/PrestaShop/ps_categoryproducts/releases/tag/v1.0.3)
* [Legal Compliance 3.0.0](https://github.com/PrestaShop/ps_legalcompliance/releases/tag/v3.0.0)

A quick update about GitHub issues: last week, [62 new issues](https://github.com/PrestaShop/PrestaShop/issues?utf8=%E2%9C%93&q=is:issue+created:2018-08-27..2018-09-02) issues have been opened in PrestaShop's core repository, and [13 fixed issues](https://github.com/PrestaShop/PrestaShop/issues?utf8=%E2%9C%93&q=is:issue+label:fixed+closed:2018-08-27..2018-09-02) have been closed.


## Code changes in the 'develop' branch (for v1.7.5.0)

### Core

* [#8744](https://github.com/PrestaShop/PrestaShop/pull/8744): CO: prefer Hook::coreRenderWidget. Thank you [@jherry](https://github.com/jherry)
* [#9343](https://github.com/PrestaShop/PrestaShop/pull/9343): Fix function comment of Module class. Thank you [@SebBareyre](https://github.com/SebBareyre)
* [#9396](https://github.com/PrestaShop/PrestaShop/pull/9396): Update version to 1.7.5.0, by [@eternoendless](https://github.com/eternoendless)
* [#10151](https://github.com/PrestaShop/PrestaShop/pull/10151): Replaced Forge URL with GitHub issues, by [@eternoendless](https://github.com/eternoendless)
* [#10155](https://github.com/PrestaShop/PrestaShop/pull/10155): fix trusted modules cache creation, by [@jocel1](https://github.com/jocel1)
* [#10182](https://github.com/PrestaShop/PrestaShop/pull/10182): FIX deprecated call to Tools::replaceByAbsoluteURL. Thank you [@axometeam](https://github.com/axometeam)
* [#10200](https://github.com/PrestaShop/PrestaShop/pull/10200): Bring back Addons Catalog controller, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#10218](https://github.com/PrestaShop/PrestaShop/pull/10218): Fix falsy value returned by upgrade script, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Back Office

* [#9305](https://github.com/PrestaShop/PrestaShop/pull/9305): Introduce ToggleColumn for Grid component, by [@matks](https://github.com/matks)
* [#9449](https://github.com/PrestaShop/PrestaShop/pull/9449): Migration of Improve -> International -> Translations page. Thank you [@rokaszygmantas](https://github.com/rokaszygmantas)
* [#9454](https://github.com/PrestaShop/PrestaShop/pull/9454): Notifications tab + new hierarchy, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#9465](https://github.com/PrestaShop/PrestaShop/pull/9465): Enable 'edit specific price' button on BO Product page which opens a pop-in, by [@matks](https://github.com/matks)
* [#10139](https://github.com/PrestaShop/PrestaShop/pull/10139): Remove legacy AdminBackup controller. Thank you [@sarjon](https://github.com/sarjon)
* [#10165](https://github.com/PrestaShop/PrestaShop/pull/10165): Add form handler for Translations settings forms. Thank you [@rokaszygmantas](https://github.com/rokaszygmantas)
* [#10169](https://github.com/PrestaShop/PrestaShop/pull/10169): Images aren't displayed in combinations, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#10170](https://github.com/PrestaShop/PrestaShop/pull/10170): Small ux optimizations. Thank you [@CaptainYouz](https://github.com/CaptainYouz)
* [#10201](https://github.com/PrestaShop/PrestaShop/pull/10201): Errors when saving memcached configuration, by [@PierreRambaud](https://github.com/PierreRambaud)


### Front Office

* [#9387](https://github.com/PrestaShop/PrestaShop/pull/9387): Fix for browser back button on product page. Thank you [@iqit-commerce](https://github.com/iqit-commerce)
* [#9456](https://github.com/PrestaShop/PrestaShop/pull/9456): Modify product canonical url and title value, by [@jolelievre](https://github.com/jolelievre)
* [#9458](https://github.com/PrestaShop/PrestaShop/pull/9458): Change brand and supplier default rule for SEO purposes, by [@jolelievre](https://github.com/jolelievre)
* [#10195](https://github.com/PrestaShop/PrestaShop/pull/10195): fix the bootstrap classes for left-column ID, by [@khouloudbelguith](https://github.com/khouloudbelguith)
* [#10207](https://github.com/PrestaShop/PrestaShop/pull/10207): Voucher button is too long in Cart. Thank you [@CaptainYouz](https://github.com/CaptainYouz)
* [#10230](https://github.com/PrestaShop/PrestaShop/pull/10230): Add magic methods on LazyArray classes for object-like use, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#10232](https://github.com/PrestaShop/PrestaShop/pull/10232): Generate front core assets, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Tests

* [#9385](https://github.com/PrestaShop/PrestaShop/pull/9385): Add eslint based on Airbnb, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#10038](https://github.com/PrestaShop/PrestaShop/pull/10038): Fixed mismatch of PHPDocs + unit tests, by [@mickaelandrieu](https://github.com/mickaelandrieu)


### Web Services (API)

* [#10117](https://github.com/PrestaShop/PrestaShop/pull/10117): Fix bug shipping number is empty in {followup}. Thank you [@jf-viguier](https://github.com/jf-viguier)


### Install

* [#9401](https://github.com/PrestaShop/PrestaShop/pull/9401): Check at installation if PrestaShop version is the latest, by [@matks](https://github.com/matks)


## Code changes in modules, themes & tools

### MBO

* [#31](https://github.com/PrestaShop/ps_mbo/pull/31): Fix error with object given to shuffle(), by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### TranslationToolsBundle

* [#44](https://github.com/PrestaShop/TranslationToolsBundle/pull/44): Add extraction of translation arrays, by [@eternoendless](https://github.com/eternoendless)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: @idnovate, @djbuch, @sarjon!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with tickets and comments [on the Forge](http://forge.prestashop.com/)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use the Forge to contribute to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

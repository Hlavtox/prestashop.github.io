---
layout: post
aliases: ["/news/coreweekly-week-41-2018"]
title:  "PrestaShop Core Weekly - Week 41 of 2018"
subtitle: "An inside look at the PrestaShop codebase"
date:   2018-10-22 16:00:00
authors: [ AntoineThomas ]
icon: icon-calendar
tags:
 - core-monthly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase during the last week, from Monday 08th to Sunday 14th of October 2018.

![Core Weekly banner](/assets/images/2017/04/core_weekly_banner.jpg)


## General messages

Dear Developers,

A network maintenance will be operated on our infrastructure during the night of Monday 22nd to Tuesday 23rd of October. The PrestaShop Addons Maketplace and its APIs will be unavailable between 0:00 and 0:30 CET, hence a 30 minutes of downtime.
The aim of this operation is to increase the company servers' network bandwidth, in order to be able to cope with the continuous growth of PrestaShop online stores in the world.


## A quick update about GitHub issues

Last week, [70 new issues](https://github.com/PrestaShop/PrestaShop/issues?utf8=%E2%9C%93&q=is:issue+created:2018-10-08..2018-10-14)  issues have been opened in PrestaShop's core repository, and [17 fixed issues](https://github.com/PrestaShop/PrestaShop/issues?utf8=%E2%9C%93&q=is:issue+label:fixed+closed:2018-10-08..2018-10-14) have been closed.

## Code changes in the 'develop' branch (for v1.7.6.0)

### Core

* [#10160](https://github.com/PrestaShop/PrestaShop/pull/10160): Migrate categories listing. Thank you [@sarjon](https://github.com/sarjon)
* [#10777](https://github.com/PrestaShop/PrestaShop/pull/10777): Migration of Shop parameters > Contact > Contacts page.. Thank you [@rokaszygmantas](https://github.com/rokaszygmantas)
* [#10797](https://github.com/PrestaShop/PrestaShop/pull/10797): Migrate Employee list . Thank you [@sarjon](https://github.com/sarjon)
* [#10864](https://github.com/PrestaShop/PrestaShop/pull/10864): Implement image source parser. Thank you [@sarjon](https://github.com/sarjon)
* [#10917](https://github.com/PrestaShop/PrestaShop/pull/10917): Add getConfiguration to PrestaShopBundle, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Back office

* [#10790](https://github.com/PrestaShop/PrestaShop/pull/10790): Migrate Employee options configuration. Thank you [@sarjon](https://github.com/sarjon)
* [#10808](https://github.com/PrestaShop/PrestaShop/pull/10808): Adjusted URL to be SSL agnostic. Thank you [@alu-](https://github.com/alu-)
* [#10924](https://github.com/PrestaShop/PrestaShop/pull/10924): Right side block of attribute and attribute groups in combination tab not appears.. Thank you [@dbadrukhiya](https://github.com/dbadrukhiya)
* [#10939](https://github.com/PrestaShop/PrestaShop/pull/10939): Fix bad annotation in AttributeGroupLang, AttributeLang and TabLang. Thank you [@Fabuloops](https://github.com/Fabuloops)


### Front office

* [#10769](https://github.com/PrestaShop/PrestaShop/pull/10769): No unset id_attribute, could be usefull to theme development. Thank you [@Piraito](https://github.com/Piraito)
* [#10867](https://github.com/PrestaShop/PrestaShop/pull/10867): Remove inline-style of Arial font. Thank you [@Mreker](https://github.com/Mreker)


## Code changes in the '1.7.5.x' branch (for v1.7.5.0)

### Core

* [#10865](https://github.com/PrestaShop/PrestaShop/pull/10865): Fix compatibility with PHP 5.6 for PS exception. Thank you [@sarjon](https://github.com/sarjon)
* [#10883](https://github.com/PrestaShop/PrestaShop/pull/10883): Missing translations, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#10905](https://github.com/PrestaShop/PrestaShop/pull/10905): Update catalog, by [@PierreRambaud](https://github.com/PierreRambaud)


### Back Office

* [#10810](https://github.com/PrestaShop/PrestaShop/pull/10810): Allow URL in search result preview to be live updated, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#10856](https://github.com/PrestaShop/PrestaShop/pull/10856): Fatal error when saving product with tags. Thank you [@rokaszygmantas](https://github.com/rokaszygmantas)
* [#10868](https://github.com/PrestaShop/PrestaShop/pull/10868): Manage backward compatibility of legacy links, by [@jolelievre](https://github.com/jolelievre)
* [#10901](https://github.com/PrestaShop/PrestaShop/pull/10901): Make Logger stdout configurable using env variables, by [@mickaelandrieu](https://github.com/mickaelandrieu)
* [#10906](https://github.com/PrestaShop/PrestaShop/pull/10906): Add new native module ps_faviconnotificationbo, by [@eternoendless](https://github.com/eternoendless)
* [#10946](https://github.com/PrestaShop/PrestaShop/pull/10946): Allow errors without field to be displayed on product form, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#10949](https://github.com/PrestaShop/PrestaShop/pull/10949): Update help panel position on legacy pages, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#10950](https://github.com/PrestaShop/PrestaShop/pull/10950): Update module breadcrumb in category page, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#10967](https://github.com/PrestaShop/PrestaShop/pull/10967): Fix Bad annotations (backport of #10939), by [@mickaelandrieu](https://github.com/mickaelandrieu)


### Tests

* [#10879](https://github.com/PrestaShop/PrestaShop/pull/10879): Add some fixes to the campaign Full, by [@fatmaBouchekoua](https://github.com/fatmaBouchekoua)
* [#10926](https://github.com/PrestaShop/PrestaShop/pull/10926): Fix typo, by [@fatmaBouchekoua](https://github.com/fatmaBouchekoua)
* [#10987](https://github.com/PrestaShop/PrestaShop/pull/10987): Add nightly tasks to Travis, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Localization

* [#10843](https://github.com/PrestaShop/PrestaShop/pull/10843): fixing typo in download_product.txt. Thank you [@antonellamarengo](https://github.com/antonellamarengo)


##  Code changes in the '1.6.1.x' branch (for v1.6.1.22)

### Core

* [#10921](https://github.com/PrestaShop/PrestaShop/pull/10921): Missing class const on cert refresh, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


## Code changes in modules, themes & tools

### PrestaShop on Docker

* [#138](https://github.com/PrestaShop/docker/pull/138): Add nightly builds on docker hub, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Auto Upgrade


* [#176](https://github.com/PrestaShop/autoupgrade/pull/176): Fix wordings without domain, by [@eternoendless](https://github.com/eternoendless)


### MBO

* [#55](https://github.com/PrestaShop/ps_mbo/pull/55): Fix #54 - Configure link after install. Thank you [@MrBaiame](https://github.com/MrBaiame)


### Favicon Notification

* [#7](https://github.com/PrestaShop/ps_faviconnotificationbo/pull/7): Change translation method, by [@clementdaubeuf](https://github.com/clementdaubeuf)

<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: @alu-, @antonellamarengo, @dbadrukhiya, @Fabuloops, @MrBaiame, @Mreker, @Piraito, @rokaszygmantas, @sarjon!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

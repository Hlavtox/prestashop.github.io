---
layout: post
aliases: ["/news/coreweekly-week-42-2018"]
slug: "coreweekly-week-42-2018"
title:  "PrestaShop Core Weekly - Week 42 of 2018"
subtitle: "An inside look at the PrestaShop codebase"
date:   2018-10-23 15:00:00
authors: [ AntoineThomas ]
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase during the last week, from Monday 15th to Sunday 21st of October 2018.

![Core Weekly banner](/assets/images/2017/04/core_weekly_banner.jpg)


## General messages

Dear Developers,

Starting today, public [PrestaShop 1.7.x nightly builds](https://console.cloud.google.com/storage/browser/prestashop-core-nightly) are available! This way, it should be easier for anyone who wants to contribute to the project to work with a recent build. Also, it means that merged pull requests will be in a build the next day for testing.

Something special happened last week: more than half of the merged pull requests are for modules.

"One more thing", as Steve Jobs used to tell: for the first time, the pull requests for the documentation are listed in the core-weekly. Documentation is very important, thank you very much to all contributors!

## A quick update about GitHub issues

Last week, [58 new issues](https://github.com/PrestaShop/PrestaShop/issues?utf8=%E2%9C%93&q=is:issue+created:2018-10-15..2018-10-21)  issues have been opened in PrestaShop's core repository, and [26 fixed issues](https://github.com/PrestaShop/PrestaShop/issues?utf8=%E2%9C%93&q=is:issue+label:fixed+closed:2018-10-15..2018-10-21) have been closed.

## Code changes in the 'develop' branch (for v1.7.6.0)

### Core

* [#10770](https://github.com/PrestaShop/PrestaShop/pull/10770): Update CacheClearer adapter. Thank you [@sarjon](https://github.com/sarjon)

### Back office

* [#10120](https://github.com/PrestaShop/PrestaShop/pull/10120): Migration of Advanced Parameters -> Import (Step 2). Thank you [@rokaszygmantas](https://github.com/rokaszygmantas)
* [#10930](https://github.com/PrestaShop/PrestaShop/pull/10930): Allow product import to change previous id_category_default when you force ID #10871. Thank you [@itisco](https://github.com/itisco)


## Code changes in the '1.7.5.x' branch (for v1.7.5.0)

### Core

* [#10933](https://github.com/PrestaShop/PrestaShop/pull/10933): Fix translation catalog, by [@eternoendless](https://github.com/eternoendless)
* [#11030](https://github.com/PrestaShop/PrestaShop/pull/11030): Harmonize migrated controllers. Thank you [@sarjon](https://github.com/sarjon)
* [#11066](https://github.com/PrestaShop/PrestaShop/pull/11066): Fix wording in wrong domain, by [@eternoendless](https://github.com/eternoendless)
* [#11068](https://github.com/PrestaShop/PrestaShop/pull/11068): Prevent CS Fixer from adding a trailing dot to the first paragraph of phpdoc, by [@eternoendless](https://github.com/eternoendless)
* [#11076](https://github.com/PrestaShop/PrestaShop/pull/11076): Fix wordings, by [@eternoendless](https://github.com/eternoendless)
* [#11078](https://github.com/PrestaShop/PrestaShop/pull/11078): Update dependency for security reason, by [@jolelievre](https://github.com/jolelievre)


### Back office

* [#10436](https://github.com/PrestaShop/PrestaShop/pull/10436): Style issue on BO. Thank you [@CaptainYouz](https://github.com/CaptainYouz)
* [#10718](https://github.com/PrestaShop/PrestaShop/pull/10718): Add missing styles on empty state SEO & Traffic page. Thank you [@CaptainYouz](https://github.com/CaptainYouz)
* [#10861](https://github.com/PrestaShop/PrestaShop/pull/10861): Fix fixed height of TinyMce fields, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#10936](https://github.com/PrestaShop/PrestaShop/pull/10936): Prevent unvalidated form without checkboxes, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#10968](https://github.com/PrestaShop/PrestaShop/pull/10968): Fix General options configuration. Thank you [@sarjon](https://github.com/sarjon)
* [#10991](https://github.com/PrestaShop/PrestaShop/pull/10991): Fix sorting issue in the SQL Manager page, by [@khouloudbelguith](https://github.com/khouloudbelguith)
* [#11032](https://github.com/PrestaShop/PrestaShop/pull/11032): Min height product image dropzone, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#11063](https://github.com/PrestaShop/PrestaShop/pull/11063): Improve PositionColumn to allow more route params, by [@jolelievre](https://github.com/jolelievre)
* [#11071](https://github.com/PrestaShop/PrestaShop/pull/11071): Avoid glitch on checkbox click, by [@jolelievre](https://github.com/jolelievre)


### Front office

* [#10447](https://github.com/PrestaShop/PrestaShop/pull/10447): Double h1 tag on category page. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#10812](https://github.com/PrestaShop/PrestaShop/pull/10812): Display the specific reference for each combination's product, by [@khouloudbelguith](https://github.com/khouloudbelguith)
* [#11015](https://github.com/PrestaShop/PrestaShop/pull/11015): Adding/Deleting voucher on checkout payment step should refresh amount on payment block, by [@tomlev](https://github.com/tomlev)
* [#11084](https://github.com/PrestaShop/PrestaShop/pull/11084): Update modules for new 1.7.5 version, by [@jolelievre](https://github.com/jolelievre)


### Tests

* [#11037](https://github.com/PrestaShop/PrestaShop/pull/11037): Fix asynchronous problem, by [@fatmaBouchekoua](https://github.com/fatmaBouchekoua)


## Code changes in modules, themes & tools

### Buy Button Lite

* [#6](https://github.com/PrestaShop/ps_buybuttonlite/pull/6): Fix wordings, by [@eternoendless](https://github.com/eternoendless)
* [#7](https://github.com/PrestaShop/ps_buybuttonlite/pull/7): Fix typo in wording, by [@eternoendless](https://github.com/eternoendless)


### Gamification

* [#23](https://github.com/PrestaShop/gamification/pull/23):  Made enable and disable update Tab status. Thank you [@alu-](https://github.com/alu-)
* [#24](https://github.com/PrestaShop/gamification/pull/24): Added travis + tests + cs fixes, by [@mickaelandrieu](https://github.com/mickaelandrieu)
* [#25](https://github.com/PrestaShop/gamification/pull/25): Optimized network calls, by [@mickaelandrieu](https://github.com/mickaelandrieu)


### Auto upgrade

* [#179](https://github.com/PrestaShop/autoupgrade/pull/179): Fix wordings, by [@eternoendless](https://github.com/eternoendless)
* [#180](https://github.com/PrestaShop/autoupgrade/pull/180): Suggest minor upgrades by default, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#181](https://github.com/PrestaShop/autoupgrade/pull/181): Remove trans_default_domain tag and rely on module translations only, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#182](https://github.com/PrestaShop/autoupgrade/pull/182): Deploying 4.4.0 of autoupgrade, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#183](https://github.com/PrestaShop/autoupgrade/pull/183): Bump version to 4.4.0, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Faceted search

* [#43](https://github.com/PrestaShop/ps_facetedsearch/pull/43): Fix [BOOM-2025] ps_facetedsearch - Filter products by the stock of matched variants, not just any of them. Thank you [@PeNov](https://github.com/PeNov)
* [#45](https://github.com/PrestaShop/ps_facetedsearch/pull/45): Bump version to 2.2.1, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#46](https://github.com/PrestaShop/ps_facetedsearch/pull/46): Deploying v2.2.1 of Faceted Search, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Google Sitemap

* [#53](https://github.com/PrestaShop/gsitemap/pull/53): Fix all reported bugs. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#55](https://github.com/PrestaShop/gsitemap/pull/55): Fix typo in wording, by [@eternoendless](https://github.com/eternoendless)
* [#56](https://github.com/PrestaShop/gsitemap/pull/56): Apply CS fixer, by [@eternoendless](https://github.com/eternoendless)


### MBO

* [#56](https://github.com/PrestaShop/ps_mbo/pull/56): Fix search, by [@MrBaiame](https://github.com/MrBaiame)
* [#57](https://github.com/PrestaShop/ps_mbo/pull/57): Translations, by [@MrBaiame](https://github.com/MrBaiame)
* [#59](https://github.com/PrestaShop/ps_mbo/pull/59): Dev, by [@MrBaiame](https://github.com/MrBaiame)
* [#60](https://github.com/PrestaShop/ps_mbo/pull/60): 1.0.8, by [@MrBaiame](https://github.com/MrBaiame)


### Favicon Notification

* [#8](https://github.com/PrestaShop/ps_faviconnotificationbo/pull/8): Use new translation method, by [@eternoendless](https://github.com/eternoendless)


###  Email Subscription

* [#31](https://github.com/PrestaShop/ps_emailsubscription/pull/31): Fix use of wordings without domain, by [@eternoendless](https://github.com/eternoendless)


### Google Analytics

* [#15](https://github.com/PrestaShop/ps_googleanalytics/pull/15): Fix wordings without domain, by [@eternoendless](https://github.com/eternoendless)

### Docker internal image


* [#17](https://github.com/PrestaShop/docker-internal-images/pull/17): Add nightly build, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#18](https://github.com/PrestaShop/docker-internal-images/pull/18): Leave gamification alone!, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


## Changes in Documentation

* [#119](https://github.com/PrestaShop/docs/pull/119): Add docs for Grid columns. Thank you [@sarjon](https://github.com/sarjon)
* [#133](https://github.com/PrestaShop/docs/pull/133):  Updated docs, by [@mickaelandrieu](https://github.com/mickaelandrieu)
* [#136](https://github.com/PrestaShop/docs/pull/136): wrong path for display.php. Thank you [@vhessam](https://github.com/vhessam)
* [#151](https://github.com/PrestaShop/docs/pull/151): Update _index.md. Thank you [@Lynxu](https://github.com/Lynxu)
* [#152](https://github.com/PrestaShop/docs/pull/152): Create mail.md. Thank you [@PaoloFalomo](https://github.com/PaoloFalomo)
* [#153](https://github.com/PrestaShop/docs/pull/153): Fix code syntax. Thank you [@jief](https://github.com/jief)
* [#154](https://github.com/PrestaShop/docs/pull/154): Update mail.md. Thank you [@PaoloFalomo](https://github.com/PaoloFalomo)
* [#155](https://github.com/PrestaShop/docs/pull/155): Added faceted search minimal docs, by [@mickaelandrieu](https://github.com/mickaelandrieu)
* [#156](https://github.com/PrestaShop/docs/pull/156): Minor fixes, by [@mickaelandrieu](https://github.com/mickaelandrieu)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: @alu-, @CaptainYouz, @itisco, @jief, @Lynxu, @MathiasReker, @PaoloFalomo, @PeNov, @rokaszygmantas, @sarjon, @vhessam!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

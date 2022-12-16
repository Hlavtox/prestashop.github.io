---
layout: post
aliases: ["/news/coreweekly-week-05-2018"]
title:  "PrestaShop Core Weekly - Week 05 of 2018"
subtitle: "An inside look at the PrestaShop codebase"
date:   2018-02-07 09:10:11
authors: [ LouiseBonnard ]
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase during the last week, from Monday 29th of January to Sunday 04th of February 2018.

![Core Weekly banner](/assets/images/2017/04/core_weekly_banner.jpg)


## General messages

… and it is here! Version 1.6.1.18 has arrived, standing ovation! We know you’ve been waiting quite some time for it, thanks for your patience. It contains more than twenty bug fixes, see the list [here]( https://www.prestashop.com/en/system/files/ps_releases/changelog_1.6.1.18.txt). Note that the 1.6 won’t be maintained after October 2018.

Also, the [PrestaShop’s developer documentation]( http://devdocs.prestashop.com) is now online - it just needs to be completed! All the technical aspects of PrestaShop will be gathered here so that theme, module or core developers can use it whenever they need.

One more word. Last week was translation focused, first with the interview of [Roberto Calisto]( http://build.prestashop.com/news/contributor-interview-roberto-calisto), who has been a great help on the [Crowdin]( https://crowdin.com/project/prestashop-official) Portuguese project, then with the monthly report. It throws very flattering light on the work accomplished so far because it is pure progress and involvement for now. How proud we are to gather such a community around!


## Code changes in the 'develop' branch (for v1.7.4.0)

### Core

* [#8674](https://github.com/PrestaShop/PrestaShop/pull/8674): Rename old paths of cache and logs for SF 3, by @quetzacoalt91.
* [#8698](https://github.com/PrestaShop/PrestaShop/pull/8698): CLDR Data layers, by @littlebigdev.
* [#8709](https://github.com/PrestaShop/PrestaShop/pull/8709): CO: OrderDetailsController should use Tools::getRemoteAddr() function instead of instead of $_SERVER['REMOTE_ADDR']. Thank you @infiniweb!
* [#8718](https://github.com/PrestaShop/PrestaShop/pull/8718): Renamed locale and currency data objects (no more use of "bag"), by @littlebigdev.


### Back office

* [#8604](https://github.com/PrestaShop/PrestaShop/pull/8604): Migration of page Shop Parameters > General > Maintenance, by @quetzacoalt91.
* [#8613](https://github.com/PrestaShop/PrestaShop/pull/8613): [-] BO : Fixes AdminController's processDeleteImage() redirect after URL. Thank you @gonssal!
* [#8672](https://github.com/PrestaShop/PrestaShop/pull/8672): Move submit button to the right in sf forms, by @quetzacoalt91.


### Installer

* [#8668](https://github.com/PrestaShop/PrestaShop/pull/8668): IN: Allow to setup the shop with SSL by default using CLI installer. Thank you @devyk!


## Code changes in the '1.7.3.x' branch (for v1.7.3.0)

### Core

* [#8713](https://github.com/PrestaShop/PrestaShop/pull/8713): String to translate for 1.7.3, by @toutantic.
* [#8719](https://github.com/PrestaShop/PrestaShop/pull/8719): Fix missing CLDR supplemental directory. Thank you @alegout!


## Code changes in the '1.6.1.x' branch (for v1.6.1.19)

### Core

* [#8536](https://github.com/PrestaShop/PrestaShop/pull/8536): Fixed for duplication of product which has both combinations and specific prices. Thank you @matrixino!
* [#8682](https://github.com/PrestaShop/PrestaShop/pull/8682): Fix error 500, result of built-in function in write context. Thank you @vschoener!


### Back office

* [#8612](https://github.com/PrestaShop/PrestaShop/pull/8612): Fix AdminController's processDeleteImage() redirect after URL. Thank you @gonssal!


### Front office

* [#8686](https://github.com/PrestaShop/PrestaShop/pull/8686): Fix the blank page when no currency defined in the shop. Thank you @azouz-jribi!

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: @alegout, @azouz-jribi, @devyk, @gonssal, @infiniweb, @matrixino and @vschoener!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with tickets and comments [on the Forge](http://forge.prestashop.com/)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](http://doc.prestashop.com/display/PS16/Contributing+code+to+PrestaShop)
 * [How to write a commit message](http://doc.prestashop.com/display/PS16/How+to+write+a+commit+message)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use the Forge to contribute to PrestaShop](http://doc.prestashop.com/display/PS16/How+to+use+the+Forge+to+contribute+to+PrestaShop). Thank you!

Happy contributin' everyone!

---
layout: post
aliases: ["/news/coreweekly-week-15-2018"]
slug: "coreweekly-week-15-2018"
title:  "PrestaShop Core Weekly - Week 15 of 2018"
subtitle: "An inside look at the PrestaShop codebase"
date:   2018-04-17 15:30:00
authors: [ AntoineThomas ]
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase during the last week, from Monday 9th to Sunday 15th of April 2018.

![Core Weekly banner](/assets/images/2017/04/core_weekly_banner.jpg)


## General messages

Developers, we hear you! The hot topic at the moment is of course the RGPD and how to handle it with PrestaShop. Please take the time to read [our article on the topic, published yesterday](http://build.prestashop.com/news/prestashop-and-gdpr/). And, of course, we are working on more content about it, including some examples.


## Code changes in the 'develop' branch (for v1.7.4.0)

### Back office

* [#8523](https://github.com/PrestaShop/PrestaShop/pull/8523): Migrate Logs page to Symfony, by @mickaelandrieu.
* [#8637](https://github.com/PrestaShop/PrestaShop/pull/8637): Update back-office menu style, by @alegout.
* [#8700](https://github.com/PrestaShop/PrestaShop/pull/8700): Admin permission detection of Role classe name. Thank you @123monsite-regis!
* [#8757](https://github.com/PrestaShop/PrestaShop/pull/8757): Prevent using "¤" and "\|" as customer name. Thank you @PierreJoube!
* [#8814](https://github.com/PrestaShop/PrestaShop/pull/8814): Module tab new subtree, by @Quetzacoalt91.
* [#8836](https://github.com/PrestaShop/PrestaShop/pull/8836): Replace Open Sans font with Vazir font for Farsi (BO default theme). Thank you @mehrshadz!
* [#8837](https://github.com/PrestaShop/PrestaShop/pull/8837): Replace Open Sans font with Vazir font for Farsi (BO new theme). Thank you @mehrshadz!
* [#8896](https://github.com/PrestaShop/PrestaShop/pull/8896): Optimize breadcrumb computation performances, by @jocel1.
* [#8909](https://github.com/PrestaShop/PrestaShop/pull/8909): Allow autoloading in modules for services use in BO, by @mickaelandrieu.
* [#8920](https://github.com/PrestaShop/PrestaShop/pull/8920): Migrate Shop Parameters -> Customer Settings. Thank you @sarjon!
* [#8944](https://github.com/PrestaShop/PrestaShop/pull/8944): Hide Logs page, by @mickaelandrieu.

### Core

* [#8883](https://github.com/PrestaShop/PrestaShop/pull/8883): Migrate ShopParameters->General page. Thank you @rokaszygmantas!
* [#8888](https://github.com/PrestaShop/PrestaShop/pull/8888): New Locale integration tests, by @LittleBigDev.
* [#8929](https://github.com/PrestaShop/PrestaShop/pull/8929): Merge 1.7.3.1 into develop, by @eternoendless.


## Code changes in the '1.7.3.x' branch (for v1.7.3.0)

### Back office

* [#8762](https://github.com/PrestaShop/PrestaShop/pull/8762): Specific price created for a cart is displayed in the front end as the product price. Thank you @roja45!
* [#8843](https://github.com/PrestaShop/PrestaShop/pull/8843): Minor install improvements, by @eternoendless.


### Core

* [#8679](https://github.com/PrestaShop/PrestaShop/pull/8679): Catch Throwable errors on CLI install and check Theme instance in context, by @Quetzacoalt91.


### Front Office

* [#8834](https://github.com/PrestaShop/PrestaShop/pull/8834): Adds missing Persian translations for data and samples. Thank you @mehrshadz!
* [#8931](https://github.com/PrestaShop/PrestaShop/pull/8931): Out of stock message display only if customer can order the product, by @mickaelandrieu.


Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: @123monsite-regis, @mehrshadz, @PierreJoube, @roja45, @rokaszygmantas, @sarjon !

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with tickets and comments [on the Forge](http://forge.prestashop.com/)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](http://doc.prestashop.com/display/PS16/Contributing+code+to+PrestaShop)
 * [How to write a commit message](http://doc.prestashop.com/display/PS16/How+to+write+a+commit+message)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use the Forge to contribute to PrestaShop](http://doc.prestashop.com/display/PS16/How+to+use+the+Forge+to+contribute+to+PrestaShop). Thank you!

Happy contributin' everyone!

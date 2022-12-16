---
layout: post
aliases: ["/news/coreweekly-week-12-2018"]
slug: "coreweekly-week-12-2018"
title:  "PrestaShop Core Weekly - Week 12 of 2018"
subtitle: "An inside look at the PrestaShop codebase"
date:   2018-03-26 09:10:11
authors: [ LouiseBonnard ]
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase during the last week, from Monday 19th to Sunday 25th of March 2018.

![Core Weekly banner](/assets/images/2017/04/core_weekly_banner.jpg)


## General messages

Hey guys, nice weekend? Have you noticed we’ve posted the [detailed schedule]( http://build.prestashop.com/news/announcing-our-2018-release-schedule) last Friday? We are really happy to share our vision for future releases as we are now planning the bare bones of PrestaShop. And for that we would love to hear your opinion. For instance, item location has disappeared from major version 1.7 but you are often asking about it. Vote for this feature on the [User Voice](http://feedback.prestashop.com) to let us know about it.

Regarding GDPR and the changes it will bring, we are currently working on a module that will be available for 1.5 to 1.7 stores. And of course it will be available before May 25th! A post will soon be posted to tell you everything about it.


## Code changes in the 'develop' branch (for v1.7.4.0)

### Back office

* [#8872](https://github.com/PrestaShop/PrestaShop/pull/8872): Validator:validateValue is not available in Symfony3, by @mickaelandrieu.


### Core

* [#8781](https://github.com/PrestaShop/PrestaShop/pull/8781): Getting Currency data from Currency data layers middleware stack, by @littlebigdev.


## Code changes in the '1.7.3.x' branch (for v1.7.3.0)

### Back office

* [#8500](https://github.com/PrestaShop/PrestaShop/pull/8500): Make sure shop list in header is scrollable with lot of items, by @quetzacoalt91.
* [#8664](https://github.com/PrestaShop/PrestaShop/pull/8664): Change employee icon, by @eternoendless.


### Front office

* [#8845](https://github.com/PrestaShop/PrestaShop/pull/8845): Fix search bar on header when it moves from hook and improve header structure #2. Thank you @slorenzini!
* [#8847](https://github.com/PrestaShop/PrestaShop/pull/8847): Override advertising module on classic template to fix image width. Thank you @slorenzini!
* [#8856](https://github.com/PrestaShop/PrestaShop/pull/8856): Fixed undefined variables when an url is called in ajax, by @mickaelandrieu.


### Core

* [#8584](https://github.com/PrestaShop/PrestaShop/pull/8584): Update toCamelCase. Thank you @neoteknic!
* [#8708](https://github.com/PrestaShop/PrestaShop/pull/8708): Debug of Tools::strReplaceFirst that do not correctly compare the return of strpos + PhpDoc. Thank you @infiniweb!
* [#8711](https://github.com/PrestaShop/PrestaShop/pull/8711): Default AJAX Relevance search sort order is wrong, by @eternoendless.
* [#8803](https://github.com/PrestaShop/PrestaShop/pull/8803): Stop full object exposure on the front end, by @eternoendless.
* [#8867](https://github.com/PrestaShop/PrestaShop/pull/8867): Rely on the right legacy container if available on modules, by @mickaelandrieu.


### Test

* [#8810](https://github.com/PrestaShop/PrestaShop/pull/8810): Check the total price in the shopping cart. Thank you @hadrich-hatem!


### Installer

* [#8858](https://github.com/PrestaShop/PrestaShop/pull/8858): Include docs when creating zip build, by @eternoendless.
* [#8860](https://github.com/PrestaShop/PrestaShop/pull/8860): Make the dezipper great again, by @eternoendless.

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: @hadrich-hatem, @infiniweb, @neoteknic and @slorenzini!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with tickets and comments [on the Forge](http://forge.prestashop.com/)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](http://doc.prestashop.com/display/PS16/Contributing+code+to+PrestaShop)
 * [How to write a commit message](http://doc.prestashop.com/display/PS16/How+to+write+a+commit+message)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use the Forge to contribute to PrestaShop](http://doc.prestashop.com/display/PS16/How+to+use+the+Forge+to+contribute+to+PrestaShop). Thank you!

Happy contributin' everyone!

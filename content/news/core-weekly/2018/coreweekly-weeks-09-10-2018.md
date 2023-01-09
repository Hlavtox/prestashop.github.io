---
layout: post
aliases: ["/news/coreweekly-weeks-09-10-2018"]
title:  "PrestaShop Core Weekly - Weeks 09 & 10 of 2018"
subtitle: "An inside look at the PrestaShop codebase"
date:   2018-03-12 09:10:11
authors: [ LouiseBonnard ]
icon: icon-calendar
tags:
 - core-monthly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase during the last two weeks, from Monday 26th of February to Sunday 11th of March 2018.

![Core Weekly banner](/assets/images/2017/04/core_weekly_banner.jpg)


## General messages

Wow, almost seventeen pull requests merged last week. Impressive! It seems that we’re back, with a lot of features and futures projects to share, and it feels very good. A [test framework]( http://build.prestashop.com/news/prestashop-test-framework) has been set, to launch a suite of functional tests and gain precious time, [version 1.7.3.0]( http://build.prestashop.com/news/prestashop-1-7-3-0-available) is out, the [release schedule]( http://build.prestashop.com/howtos/misc/2018-release-schedule) also, and the detailed roadmap is on its way… we are pretty eager to be on the road again with you all! Stay connected!


## Code changes in the 'develop' branch (for v1.7.4.0)

### Core

* [#8689](https://github.com/PrestaShop/PrestaShop/pull/8689): Fix translator in prod mode, by @quetzacoalt91.
* [#8811](https://github.com/PrestaShop/PrestaShop/pull/8811): Merge 1.7.3.x, by @eternoendless.


## Code changes in the '1.7.3.x' branch (for v1.7.3.0)

### Back office

* [#8234](https://github.com/PrestaShop/PrestaShop/pull/8234): Fixed bug on save specific price priority for specific product. Thank you @christianverardi!
* [#8476](https://github.com/PrestaShop/PrestaShop/pull/8476): Fix customer search in new order form. Thank you @uebix!
* [#8525](https://github.com/PrestaShop/PrestaShop/pull/8525): "No tax" price option is now well saved in admin product page, by @littlebigdev.
* [#8618](https://github.com/PrestaShop/PrestaShop/pull/8618): Fix type warning in order detail, by @eternoendless.
* [#8648](https://github.com/PrestaShop/PrestaShop/pull/8648): Fix modal backdrop not removed when uninstalling a module. Thank you @alegout!
* [#8696](https://github.com/PrestaShop/PrestaShop/pull/8696): Fix translation issue during language install, by @tomlev.
* [#8714](https://github.com/PrestaShop/PrestaShop/pull/8714): Update loaded details from database on module action, by @quetzacoalt91.
* [#8725](https://github.com/PrestaShop/PrestaShop/pull/8725): Replace Google+ link on BO footer by Youtube link. Thank you @slorenzini!


### Front office

* [#8522](https://github.com/PrestaShop/PrestaShop/pull/8522): Fixed specific price percentage rounding on front product page, by @littlebigdev.


### Core

* [#8277](https://github.com/PrestaShop/PrestaShop/pull/8277): CustomerAddressFormatter states were queried without the status (active) check causing disabling states in BO useless. Thank you @yuxblank!
* [#8462](https://github.com/PrestaShop/PrestaShop/pull/8462): Fix empty module return on actionEmailSendBefore breaks all email send. Thank you @mdweb-lille!
* [#8669](https://github.com/PrestaShop/PrestaShop/pull/8669): Make sure all adresses are reset on cart. Thank you @prestaworks!
* [#8795](https://github.com/PrestaShop/PrestaShop/pull/8795): Minor improvements during install, by @eternoendless.


### Test

* [#8746](https://github.com/PrestaShop/PrestaShop/pull/8746): Make file copy on ModuleSelfConfiguration mockable, by @eternoendless.
* [#8815](https://github.com/PrestaShop/PrestaShop/pull/8815): Re-enable functional tests, by @fatmabouchekoua.


### Installer

* [#8806](https://github.com/PrestaShop/PrestaShop/pull/8806): Sample products in FA. Thank you @mehrshadz!

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: @alegout, @christianverardi, @mdweb-lille, @mehrshadz, @prestaworks, @slorenzini, @uebix and @yuxblank!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with tickets and comments [on the Forge](http://forge.prestashop.com/)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](http://doc.prestashop.com/display/PS16/Contributing+code+to+PrestaShop)
 * [How to write a commit message](http://doc.prestashop.com/display/PS16/How+to+write+a+commit+message)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use the Forge to contribute to PrestaShop](http://doc.prestashop.com/display/PS16/How+to+use+the+Forge+to+contribute+to+PrestaShop). Thank you!

Happy contributin' everyone!

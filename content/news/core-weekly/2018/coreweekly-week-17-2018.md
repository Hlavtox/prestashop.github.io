---
layout: post
aliases: ["/news/coreweekly-week-17-2018"]
title:  "PrestaShop Core Weekly - Week 17 of 2018"
subtitle: "An inside look at the PrestaShop codebase"
date:   2018-05-02 12:30:00
authors: [ AntoineThomas ]
icon: icon-calendar
tags:
 - core-monthly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase during the last week, from Monday 23rd to Sunday 29th of April 2018.

![Core Weekly banner](/assets/images/2017/04/core_weekly_banner.jpg)


## General messages

Dear contributors, many Pull Requests from the community have been merged last week and that's great! In order to simplify the contributing experience, I would like to have your feedback on these questions:

* What are your current difficulties to submit a Pull Request on [PrestaShop Core repository](https://github.com/PrestaShop/PrestaShop)?
* What should we improve?
* What documentation is missing?
* Do you have other ideas?

Please, feel free to answer and discuss via [the forum on this dedicated thread](https://www.prestashop.com/forums/topic/790373-contributing-to-prestashop-core-should-become-more-easy/) :-)


## Code changes in the 'develop' branch (for v1.7.4.0)

### Back office
* [#8830](https://github.com/PrestaShop/PrestaShop/pull/8830): Fix uninitialized $moreStepLabels in AdminImportController. Thank you @popstas!
* [#8895](https://github.com/PrestaShop/PrestaShop/pull/8895): Allow override of every modern template, by @mickaelandrieu.
* [#8908](https://github.com/PrestaShop/PrestaShop/pull/8908): Refactored Form Handling management, by @mickaelandrieu.
* [#8916](https://github.com/PrestaShop/PrestaShop/pull/8916): Add tips in the back office to improve user experience. Thank you @sLorenzini!
* [#8927](https://github.com/PrestaShop/PrestaShop/pull/8927): Remove default theme schemes (no longer used), by @eternoendless.
* [#8933](https://github.com/PrestaShop/PrestaShop/pull/8933): [BO] Fix bug on saving store hours. Thank you @SebBareyre!
* [#8945](https://github.com/PrestaShop/PrestaShop/pull/8945): Return default values when api is unavailable, by @Quetzacoalt91.
* [#8947](https://github.com/PrestaShop/PrestaShop/pull/8947): Hooks for recommended modules & themes, by @Quetzacoalt91.
* [#8979](https://github.com/PrestaShop/PrestaShop/pull/8979): Move administration page to proper location. Thank you @sarjon!


### Front Office
* [#8833](https://github.com/PrestaShop/PrestaShop/pull/8833): Hide empty list if all variations are out of stock. Thank you @PhpMadman!

### Core
* [#8831](https://github.com/PrestaShop/PrestaShop/pull/8831): Better handling of invalid modules from Addons API, by @mickaelandrieu.
* [#8935](https://github.com/PrestaShop/PrestaShop/pull/8935): CLDR : Replace legacy number and price formatting, by @LittleBigDev.
* [#8954](https://github.com/PrestaShop/PrestaShop/pull/8954): Allowed robots access to assets requierd to be mobile-friendly. Thank you @PhpMadman!
* [#8959](https://github.com/PrestaShop/PrestaShop/pull/8959): Able to pass hook as a parameter. Thank you @DonNhh!
* [#8970](https://github.com/PrestaShop/PrestaShop/pull/8970): Improved readability. Thank you @michaelKaefer!
* [#8976](https://github.com/PrestaShop/PrestaShop/pull/8976): Set cache driver in container instead of env var CACHE_DRIVER, by @Quetzacoalt91.
* [#8980](https://github.com/PrestaShop/PrestaShop/pull/8980): Remove deprecated message for DataCollectorInterface. Thank you @PierreRambaud!
* [#8982](https://github.com/PrestaShop/PrestaShop/pull/8982): Merge 1.7.3.x into develop, by @eternoendless.


### Tests
* [#8939](https://github.com/PrestaShop/PrestaShop/pull/8939): Adaptation of the test for the version on the developed branch. Thank you @fouratachour!
* [#8983](https://github.com/PrestaShop/PrestaShop/pull/8983): Parallelize builds. Thank you @PierreRambaud!


### Install
* [#8981](https://github.com/PrestaShop/PrestaShop/pull/8981): Set explicit version of MySQL in docker-compose.yml, by @Quetzacoalt91.


## Code changes in the '1.7.3.x' branch (for v1.7.3.1)

### Back office
* [#8752](https://github.com/PrestaShop/PrestaShop/pull/8752): Check product availability before validating orders, by @alegout.
* [#8975](https://github.com/PrestaShop/PrestaShop/pull/8975): Fix broken "you must first create a new language" link in BO Translations, by @eternoendless.


### Core
* [#8973](https://github.com/PrestaShop/PrestaShop/pull/8973): Fixed undefined class constant, by @eternoendless.


### Install
* [#8949](https://github.com/PrestaShop/PrestaShop/pull/8949): Remove addition of . folder in release archives, by @Quetzacoalt91.

### Localization Pack
* [#8832](https://github.com/PrestaShop/PrestaShop/pull/8832): Update Iran tax rate. Thank you @mehrshadz!



Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: @DonNhh, @fouratachour, @mehrshadz, @michaelKaefer, @PhpMadman, @popstas, @sarjon, @SebBareyre, @sLorenzini  !

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with tickets and comments [on the Forge](http://forge.prestashop.com/)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](http://doc.prestashop.com/display/PS16/Contributing+code+to+PrestaShop)
 * [How to write a commit message](http://doc.prestashop.com/display/PS16/How+to+write+a+commit+message)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use the Forge to contribute to PrestaShop](http://doc.prestashop.com/display/PS16/How+to+use+the+Forge+to+contribute+to+PrestaShop). Thank you!

Happy contributin' everyone!

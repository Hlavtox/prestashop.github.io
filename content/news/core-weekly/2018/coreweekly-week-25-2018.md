---
layout: post
aliases: ["/news/coreweekly-week-25-2018"]
title:  "PrestaShop Core Weekly - Week 25 of 2018"
subtitle: "An inside look at the PrestaShop codebase"
date:   2018-06-27 12:00:00
authors: [ AntoineThomas ]
icon: icon-calendar
tags:
 - core-monthly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase during the last week, from Monday 18th of June to Sunday 24th of June 2018.

![Core Weekly banner](/assets/images/2017/04/core_weekly_banner.jpg)


## General messages

Hey guys, how are you? I guess that some of you could be interested in a better insight into the PrestaShop project evolution. You can now have a look at the [public roadmap on Github](https://github.com/PrestaShop/PrestaShop/projects/1)!

A word about next releases: while the 1.7.4 still needs some work to be released, we will release soon some maintenance releases of 1.7.3.x and 1.6.1.x.

Also, in this Core Weekly, you will find updates about a module. A lot of work has been done on the Auto Upgrade module. Its second beta has been released this week, [v4.0.0-beta.2](https://github.com/PrestaShop/autoupgrade/releases/tag/v4.0.0-beta.2), thanks to the feedback of many testers. Thank you very much to everyone who helps to improve it!

I will try to give more details in the future in order to give you a better overview of the activity on the PrestaShop project at large. Please leave a comment to let us know what information interests you.



## Code changes in the 'develop' branch (for v1.7.5.0)

### Core

* [#9066](https://github.com/PrestaShop/PrestaShop/pull/9066): Refactor Dispatcher::useDefaultController(). Thank you [@michaelKaefer](https://github.com/michaelKaefer)
* [#9116](https://github.com/PrestaShop/PrestaShop/pull/9116): Migrate localization page. Thank you [@sarjon](https://github.com/sarjon)
* [#9174](https://github.com/PrestaShop/PrestaShop/pull/9174): Added a service to manage PrestaShop versions (may deprecate _PS_VERSION_). Thank you [@michaelKaefer](https://github.com/michaelKaefer)
* [#9176](https://github.com/PrestaShop/PrestaShop/pull/9176): Migrate "Improve > International > Localization > Geolocation" page . Thank you [@sarjon](https://github.com/sarjon)
* [#9192](https://github.com/PrestaShop/PrestaShop/pull/9192): Migrate Payment methods page. Thank you [@sarjon](https://github.com/sarjon)
* [#9198](https://github.com/PrestaShop/PrestaShop/pull/9198): Add use statement for AppKernel, by [@mickaelandrieu](https://github.com/mickaelandrieu)
* [#9204](https://github.com/PrestaShop/PrestaShop/pull/9204): Remove leftover routing files. Thank you [@sarjon](https://github.com/sarjon)


### Back Office

* [#9137](https://github.com/PrestaShop/PrestaShop/pull/9137): Improve routing of PrestaShop application, by [@mickaelandrieu](https://github.com/mickaelandrieu)
* [#9195](https://github.com/PrestaShop/PrestaShop/pull/9195): Fixed mixed up display in some cases at partial refunds. Thank you [@paeddl](https://github.com/paeddl)


### Front Office

* [#9097](https://github.com/PrestaShop/PrestaShop/pull/9097): Fix phone fieldtype. Thank you [@rdy4ever](https://github.com/rdy4ever)


### tests

* [#9131](https://github.com/PrestaShop/PrestaShop/pull/9131): Add export shopping carts scenario, by [@fatmaBouchekoua](https://github.com/fatmaBouchekoua)
* [#9150](https://github.com/PrestaShop/PrestaShop/pull/9150): Add dockerfile for single container run of E2E, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Web Service

* [#9202](https://github.com/PrestaShop/PrestaShop/pull/9202): Preserve position in category when adding a new Product using Web services. Thank you [@Shopmonauten](https://github.com/Shopmonauten)


## Code changes in the '1.7.4.x' branch (for v1.7.4.0)

### Back Office

* [#9194](https://github.com/PrestaShop/PrestaShop/pull/9194): Handle 1.7 method in update function 'add_new_tab', by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Localization Pack

* [#9196](https://github.com/PrestaShop/PrestaShop/pull/9196): Fix wrong translation domain, by [@eternoendless](https://github.com/eternoendless)
* [#9197](https://github.com/PrestaShop/PrestaShop/pull/9197): Fix duplicate wording, by [@eternoendless](https://github.com/eternoendless)
* [#9200](https://github.com/PrestaShop/PrestaShop/pull/9200): Fix duplicate wording, by [@eternoendless](https://github.com/eternoendless)



## Code changes in the '1.6.1.x' branch (for v1.6.1.2O)

### Core

* [#9141](https://github.com/PrestaShop/PrestaShop/pull/9141): Use https no http employee class. Thank you [@okom3pom](https://github.com/okom3pom)


## Code changes in modules

### Auto Upgrade

* [#78](https://github.com/PrestaShop/autoupgrade/pull/78): Update wording, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#79](https://github.com/PrestaShop/autoupgrade/pull/79): Create issue template for bug report, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#83](https://github.com/PrestaShop/autoupgrade/pull/83): Avoid files to be generated outside the admin folder, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#84](https://github.com/PrestaShop/autoupgrade/pull/84): Always load default conf data before saved conf files, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#85](https://github.com/PrestaShop/autoupgrade/pull/85): Stop upgrade process if zip file can't be closed, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#86](https://github.com/PrestaShop/autoupgrade/pull/86): Disable modules with 1.6 method, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: @michaelKaefer, @okom3pom, @paeddl, @rdy4ever, @sarjon, @Shopmonauten!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with tickets and comments [on the Forge](http://forge.prestashop.com/)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](http://doc.prestashop.com/display/PS16/Contributing+code+to+PrestaShop)
 * [How to write a commit message](http://doc.prestashop.com/display/PS16/How+to+write+a+commit+message)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use the Forge to contribute to PrestaShop](http://doc.prestashop.com/display/PS16/How+to+use+the+Forge+to+contribute+to+PrestaShop). Thank you!

Happy contributin' everyone!

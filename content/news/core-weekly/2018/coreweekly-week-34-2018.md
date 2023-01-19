---
layout: post
aliases: ["/news/coreweekly-week-34-2018"]
title:  "PrestaShop Core Weekly - Week 34 of 2018"
subtitle: "An inside look at the PrestaShop codebase"
date:   2018-08-28 10:45:00
authors: [ AntoineThomas ]
icon: icon-calendar
tags:
 - core-monthly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase during the last week, from Monday 20th to Sunday 26th of August 2018.

![Core Weekly banner](/assets/images/2017/04/core_weekly_banner.jpg)


## General messages

Last week, we finally achieved the migration from our good old Forge to GitHub! It means that if you want to:

* [Create a bug report or a feature request](https://github.com/PrestaShop/PrestaShop/issues/new/choose) about PrestaShop 1.6.x, 1.7.x or a module,
* Look at the [roadmap](https://github.com/PrestaShop/PrestaShop/projects/1),
* Find something to fix for the next release in the [backlog](https://github.com/PrestaShop/PrestaShop/projects/2)

You must now go to the [PrestaShop GitHub repository](https://github.com/PrestaShop/PrestaShop). You will see that GitHub is very easy to use, that it has a very good user documentation, and that you don’t need to be a developer to use it.

Quick reminder: [PS Day Milano](https://prestashopday.com/it/) is due in one month so it's time to schedule your trip to the best place to meet all of our Italian ecosystem. And thanks to PrestaShop's partner MailChimp, [150 free tickets](https://www.eventbrite.com/e/biglietti-prestashop-day-milano-44793298963?aff=BuildMailChimp150ticks&discount=MailChimptioffreilbiglietto) are available this week! What are you waiting to get yours? ;-)


## Code changes in the 'develop' branch (for v1.7.5.0)

### Core

* [#9437](https://github.com/PrestaShop/PrestaShop/pull/9437): Introducing HookDispatcherInterface. Thank you [@sarjon](https://github.com/sarjon)
* [#9440](https://github.com/PrestaShop/PrestaShop/pull/9440): Ease CustomerAddressForm customization, by [@mickaelandrieu](https://github.com/mickaelandrieu)
* [#9451](https://github.com/PrestaShop/PrestaShop/pull/9451): Replace PrestaTrust property with setter, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#9461](https://github.com/PrestaShop/PrestaShop/pull/9461): Update Readme, by [@eternoendless](https://github.com/eternoendless)
* [#9467](https://github.com/PrestaShop/PrestaShop/pull/9467): Build core theme using Webpack 4 and jQuery 2.2.4, by [@eternoendless](https://github.com/eternoendless)
* [#9470](https://github.com/PrestaShop/PrestaShop/pull/9470): Refactored the Grid component, by [@mickaelandrieu](https://github.com/mickaelandrieu)
* [#9474](https://github.com/PrestaShop/PrestaShop/pull/9474): CO: files can not be accessed. Thank you [@idnovate](https://github.com/idnovate)
* [#10138](https://github.com/PrestaShop/PrestaShop/pull/10138): Avoid a DB query in Address:isUsed() in case of new Address. Thank you [@djbuch](https://github.com/djbuch)


### Back Office

* [#8710](https://github.com/PrestaShop/PrestaShop/pull/8710): Improved Product catalogAction, by [@mickaelandrieu](https://github.com/mickaelandrieu)
* [#9228](https://github.com/PrestaShop/PrestaShop/pull/9228): Migrate module positions, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#9310](https://github.com/PrestaShop/PrestaShop/pull/9310): Migrate "Configure > Advanced Parameters > Webservices" - part 1 (configuration form), by [@matks](https://github.com/matks)
* [#9352](https://github.com/PrestaShop/PrestaShop/pull/9352): Fix 'recommended modules' popin behavior in BO, by [@matks](https://github.com/matks)
* [#9407](https://github.com/PrestaShop/PrestaShop/pull/9407): Display NOK PrestaShop requirements, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#9430](https://github.com/PrestaShop/PrestaShop/pull/9430): Update modern forms layout. Thank you [@sarjon](https://github.com/sarjon)
* [#9447](https://github.com/PrestaShop/PrestaShop/pull/9447): Migrate Backup page. Thank you [@sarjon](https://github.com/sarjon)
* [#9450](https://github.com/PrestaShop/PrestaShop/pull/9450): Modify Link::getAdminLink in MultipleShop mode, by [@jolelievre](https://github.com/jolelievre)
* [#9466](https://github.com/PrestaShop/PrestaShop/pull/9466): fix combination generation, by [@tomlev](https://github.com/tomlev)
* [#10042](https://github.com/PrestaShop/PrestaShop/pull/10042): With undefined function call (Fixed #10041), by [@mickaelandrieu](https://github.com/mickaelandrieu)


### Front Office

* [#9405](https://github.com/PrestaShop/PrestaShop/pull/9405): Error when adding product in cart or editing quantity, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#9462](https://github.com/PrestaShop/PrestaShop/pull/9462): Fix wrong rules in robots.txt, by [@eternoendless](https://github.com/eternoendless)
* [#9463](https://github.com/PrestaShop/PrestaShop/pull/9463): Change the default redirection behaviour to product category, by [@jolelievre](https://github.com/jolelievre)
* [#9469](https://github.com/PrestaShop/PrestaShop/pull/9469): Do not display product Specific References if empty, by [@matks](https://github.com/matks)


### Tests

* [#9468](https://github.com/PrestaShop/PrestaShop/pull/9468): Apply coding styles (aka "phase 2"), by [@mickaelandrieu](https://github.com/mickaelandrieu)
* [#10089](https://github.com/PrestaShop/PrestaShop/pull/10089): Wrong bash conditions in check_file_syntax file, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#10126](https://github.com/PrestaShop/PrestaShop/pull/10126): Reduce Travis jobs, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#10127](https://github.com/PrestaShop/PrestaShop/pull/10127): Apply php-cs-fixer, by [@matks](https://github.com/matks)
* [#10129](https://github.com/PrestaShop/PrestaShop/pull/10129): Fix phpunit.xml indentation, by [@matks](https://github.com/matks)


### Install

* [#9414](https://github.com/PrestaShop/PrestaShop/pull/9414): Add arabic language in installer, by [@LouiseBonnard](https://github.com/LouiseBonnard)
* [#9464](https://github.com/PrestaShop/PrestaShop/pull/9464): Fix geolocation whitelist, by [@rGaillard](https://github.com/rGaillard)
* [#10104](https://github.com/PrestaShop/PrestaShop/pull/10104): Add Latvian language in the installer, by [@LouiseBonnard](https://github.com/LouiseBonnard)
* [#10106](https://github.com/PrestaShop/PrestaShop/pull/10106): Add Galician language in the installer, by [@LouiseBonnard](https://github.com/LouiseBonnard)


## Code changes in modules, themes & tools

### Auto Upgrade

* [#133](https://github.com/PrestaShop/autoupgrade/pull/133): Use a single folder for md5 files, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#138](https://github.com/PrestaShop/autoupgrade/pull/138): Publishing v4.1.0, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#141](https://github.com/PrestaShop/autoupgrade/pull/141): Fix undefined class Tools, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#142](https://github.com/PrestaShop/autoupgrade/pull/142): Bump version to 4.1.0, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#144](https://github.com/PrestaShop/autoupgrade/pull/144): Revert "Force composer autoload to be appended", by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#145](https://github.com/PrestaShop/autoupgrade/pull/145): Check bootstrap.php before require, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Dashboard Products

### Translation Files

* [#3](https://github.com/PrestaShop/TranslationFiles/pull/3): Add files for 1.7.5.0, by [@PierreRambaud](https://github.com/PierreRambaud)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: @idnovate, @djbuch, @sarjon!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with tickets and comments [on the Forge](http://forge.prestashop.com/)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use the Forge to contribute to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

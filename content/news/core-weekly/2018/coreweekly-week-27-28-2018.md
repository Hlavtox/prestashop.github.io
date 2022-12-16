---
layout: post
aliases: ["/news/coreweekly-week-27-28-2018"]
title:  "PrestaShop Core Weekly - Weeks 27 & 28 of 2018"
subtitle: "An inside look at the PrestaShop codebase"
date:   2018-07-18 09:10:11
authors: [ LouiseBonnard ]
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase during the last two weeks, from Monday 02nd to Sunday 15th of July 2018.

![Core Weekly banner](/assets/images/2017/04/core_weekly_banner.jpg)


## General messages

Oh it feels good to be back, live from the Core Weekly! As Antoine is enjoying his holidays, I take up the reins, just to let you know what dev-changes happened during those last two weeks. And the first thing I can tell is that plenty happened! Indeed, about forty pull requests have been merged. A real World Cup score, right?

A lot of them regard bug fixes for PrestaShop 1.7.4.0. Consequently, a new patch version has been launched last Monday. Please welcome [PrestaShop 1.7.4.1](http://build.prestashop.com/news/prestashop-1-7-4-1-maintenance-release)! Upgrading is still a bit sensitive, make sure you use the right module before; it ought to be version 4.0 of the 1-click upgrade, <a href="https://github.com/PrestaShop/autoupgrade/releases/download/v4.0.0-beta.3/autoupgrade-v4.0.0-beta.3.zip">currently available as a beta on GitHub</a>, instead of the version 3.0 available on the marketplace.

Also, you are probably aware of it already but who said we cannot write it again: we are very proud and thrilled to present our online [roadmap](https://github.com/PrestaShop/PrestaShop/projects/1). Making the roadmap public was one of our great wish for 2018, it is part of our plan to offer a clearer view of the future improvements and features we want to include in the software. Have a look at it!


## Code changes in the 'develop' branch (for v1.7.5.0)

### Back office

* [#9235](https://github.com/PrestaShop/PrestaShop/pull/9235): Corrects a bug when importing store contacts. Thank you @djbuch!
* [#9242](https://github.com/PrestaShop/PrestaShop/pull/9242): Introducing reusable way to display KPIs blocks in Back Office modern pages. Thank you @rokaszygmantas!
* [#9255](https://github.com/PrestaShop/PrestaShop/pull/9255): Fix rendering of theme catalog page, by @mickaelandrieu.
* [#9265](https://github.com/PrestaShop/PrestaShop/pull/9265): Can't upload an image in the product page. Thank you @pierrerambaud!
* [#9267](https://github.com/PrestaShop/PrestaShop/pull/9267): Unable to copy theme translations. Thank you @vytsci!
* [#9286](https://github.com/PrestaShop/PrestaShop/pull/9286): Grid/reset action, by @mickaelandrieu.
* [#9300](https://github.com/PrestaShop/PrestaShop/pull/9300): Fix grid sorting by. Thank you @matks!
* [#9306](https://github.com/PrestaShop/PrestaShop/pull/9306): Add a link to the addons' favicon generator. Thank you @marionf!


### Core

* [#9094](https://github.com/PrestaShop/PrestaShop/pull/9094): Migrate Improve > Shipping > Preferences controller. Thank you @rokaszygmantas!
* [#9120](https://github.com/PrestaShop/PrestaShop/pull/9120): Fix empty text transformer to not treat zero as empty text. Thank you @rokaszygmantas!
* [#9234](https://github.com/PrestaShop/PrestaShop/pull/9234): Fix override handling when PS_DISABLE_OVERRIDES is used, by @jocel1.
* [#9241](https://github.com/PrestaShop/PrestaShop/pull/9241): Fix Version service namepsace usage. Thank you @sarjon!
* [#9243](https://github.com/PrestaShop/PrestaShop/pull/9243): Fix show sql action in logs page. Thank you @sarjon!
* [#9250](https://github.com/PrestaShop/PrestaShop/pull/9250): Implement addBefore() & addAfter() methods of ColumnCollection. Thank you @sarjon!
* [#9254](https://github.com/PrestaShop/PrestaShop/pull/9254): Merge 1.7.4.x in develop. Thank you @pierrerambaud!
* [#9256](https://github.com/PrestaShop/PrestaShop/pull/9256): Improve resolving of column options. Thank you @sarjon!
* [#9257](https://github.com/PrestaShop/PrestaShop/pull/9257): problem overriding getRobotsContent in Tools.php. Thank you @fransuisse!
* [#9264](https://github.com/PrestaShop/PrestaShop/pull/9264): Update cart.js. Thank you @mehdi-ghezal!
* [#9282](https://github.com/PrestaShop/PrestaShop/pull/9282): Cleanup ModuleTemplateLoader. Thank you @sarjon!
* [#9283](https://github.com/PrestaShop/PrestaShop/pull/9283): Update column naming. Thank you @sarjon!
* [#9293](https://github.com/PrestaShop/PrestaShop/pull/9293): Rename routing file catalog.yml to _catalog.yml to follow routing structure. Thank you @sarjon!


### Tests

* [#9284](https://github.com/PrestaShop/PrestaShop/pull/9284): Add tests for grid. Thank you @sarjon!
* [#9290](https://github.com/PrestaShop/PrestaShop/pull/9290): Fix grid tests after column names update. Thank you @sarjon!


## Code changes in the '1.7.4.x' branch (for v1.7.4.0)

### Back office

* [#9245](https://github.com/PrestaShop/PrestaShop/pull/9245): Can't create or edit a category. Thank you @pierrerambaud!
* [#9261](https://github.com/PrestaShop/PrestaShop/pull/9261): Update Controller name for link generation to modules catalog, by @quetzacoalt91.
* [#9268](https://github.com/PrestaShop/PrestaShop/pull/9268): Added .htaccess to var folder, by @mickaelandrieu.
* [#9270](https://github.com/PrestaShop/PrestaShop/pull/9270): Apache 2.4 configuration. Thank you @pierrerambaud!
* [#9297](https://github.com/PrestaShop/PrestaShop/pull/9297): Fix display when a module uses $this->bootstrap = false;. Thank you @prestamodule!
* [#9299](https://github.com/PrestaShop/PrestaShop/pull/9299): Fix error while duplicating a product when catalog specific price rules are stored, by @tomlev.
* [#9311](https://github.com/PrestaShop/PrestaShop/pull/9311): Apply shop context in configuration, by @quetzacoalt91.


### Front office

* [#9252](https://github.com/PrestaShop/PrestaShop/pull/9252): Add combinations in cart summary. Thank you @marionf!
* [#9270](https://github.com/PrestaShop/PrestaShop/pull/9270): Apache 2.4 configuration. Thank you @pierrerambaud!
* [#9295](https://github.com/PrestaShop/PrestaShop/pull/9295): Fix free shipping display on cart, by @tomlev.
* [#9315](https://github.com/PrestaShop/PrestaShop/pull/9315): Fix not visible category display, by @tomlev.


### Core

* [#9101](https://github.com/PrestaShop/PrestaShop/pull/9101): Fix have cart rule today, by @jocel1.
* [#9220](https://github.com/PrestaShop/PrestaShop/pull/9220): Ability to use widget block from specific hook. Thank you @kpodemski!
* [#9237](https://github.com/PrestaShop/PrestaShop/pull/9237): Fixed bug with friendly URLs and Media Servers. Thank you @lucasrolff!
* [#9269](https://github.com/PrestaShop/PrestaShop/pull/9269): Update ps_themecusto to version 1.0.6, by @toutantic.
* [#9288](https://github.com/PrestaShop/PrestaShop/pull/9288): Fix Cart::isVirtualCart() method when cart is empty. Thank you @prestamodule!
* [#9298](https://github.com/PrestaShop/PrestaShop/pull/9298): Fix/remove mbo from tests, by @mickaelandrieu.


### Installer

* [#9258](https://github.com/PrestaShop/PrestaShop/pull/9258): Limit subquery results in upgrade sql 1.7.0.0, by @quetzacoalt91.
* [#9271](https://github.com/PrestaShop/PrestaShop/pull/9271): Catch more exceptions during install & display the error intead of a JS error, by @rgaillard.
* [#9302](https://github.com/PrestaShop/PrestaShop/pull/9302): Reduce the number of ajax calls if the fixtures are not too larges and if there's enough memory available, by @jocel1.


## Code change in modules

### Auto Upgrade

* [#96](https://github.com/PrestaShop/autoupgrade/pull/96): Use openssl for create key/iv if available, by [@rGaillard](https://github.com/rGaillard)


### Theme customization

* [#2](https://github.com/PrestaShop/ps_themecusto/pull/2): Many updates & corrections, by [@Adrienaddons](https://github.com/Adrienaddons)
* [#1](https://github.com/PrestaShop/ps_themecusto/pull/1): Fix broken links in README, by [@matks](https://github.com/matks)


### MBO

* [#14](https://github.com/PrestaShop/ps_mbo/pull/14): Fix footer display + Fix translations + Fix recommended modules tab. Thank you [@MrBaiame](https://github.com/MrBaiame)
* [#13](https://github.com/PrestaShop/ps_mbo/pull/13): 1.0.7. Thank you [@MrBaiame](https://github.com/MrBaiame)
* [#12](https://github.com/PrestaShop/ps_mbo/pull/12): Ident, tabs, and other things =), by [@PierreRambaud](https://github.com/PierreRambaud)
* [#11](https://github.com/PrestaShop/ps_mbo/pull/11): Fix recommended modules + 1.0.6. Thank you [@MrBaiame](https://github.com/MrBaiame)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: @djbuch, @fransuisse, @kpodemski, @lucasrolff, @marionf, @matks, @mehdi-ghezal, @MrBaiame, @pierrerambaud, @prestamodule, @rokaszygmantas, @sarjon and @vytsci!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with tickets and comments [on the Forge](http://forge.prestashop.com/)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](http://doc.prestashop.com/display/PS16/Contributing+code+to+PrestaShop)
 * [How to write a commit message](http://doc.prestashop.com/display/PS16/How+to+write+a+commit+message)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use the Forge to contribute to PrestaShop](http://doc.prestashop.com/display/PS16/How+to+use+the+Forge+to+contribute+to+PrestaShop). Thank you!

Happy contributin' everyone!

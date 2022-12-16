---
layout: post
aliases: ["/news/coreweekly-week-21-2018"]
title:  "PrestaShop Core Weekly - Week 21 of 2018"
subtitle: "An inside look at the PrestaShop codebase"
date:   2018-05-30 17:10:00
authors: [ AntoineThomas ]
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase during the last week, from Monday 21st of May to Sunday 27th of May 2018.

![Core Weekly banner](/assets/images/2017/04/core_weekly_banner.jpg)


## General messages

Last week, a few updates have been done on the core, plus on some native modules. You might also have to update your theme. Guess what: this is still in order to improve the GDPR compliance of your PrestaShop store. You can read the details on Build:

* [Update Your Store For GDPR](http://build.prestashop.com/news/update-your-prestashop-store/)
* [Release Of PrestaShop 1.7.3.3 And 1.6.1.19](http://build.prestashop.com/news/prestashop-1-7-3-3-1-6-1-19-maintenance-releases/)

Now, the most interesting part of this news: if you live in Paris, or if you need a good reason to come in Paris, [PrestaShop Day](https://prestashopday.com) is in 2 weeks. We really hope to meet you there ;-)

## Code changes in the 'develop' branch (for v1.7.5.0)

### Core

* [#9037](https://github.com/PrestaShop/PrestaShop/pull/9037): Permit IDE completion with PHP doc. Thank you [@MatthieuMota](https://github.com/MatthieuMota)
* [#9039](https://github.com/PrestaShop/PrestaShop/pull/9039): Ajax will never die, by [@jocel1](https://github.com/jocel1)
* [#9053](https://github.com/PrestaShop/PrestaShop/pull/9053): Add missing package-lock.json files, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#9064](https://github.com/PrestaShop/PrestaShop/pull/9064): Fixed list of activated modules, by [@mickaelandrieu](https://github.com/mickaelandrieu)
* [#9095](https://github.com/PrestaShop/PrestaShop/pull/9095): Fix translations order settings and remove unused templates. Thank you [@rokaszygmantas](https://github.com/rokaszygmantas)
* [#9096](https://github.com/PrestaShop/PrestaShop/pull/9096): Clean up service yml files. Thank you [@sarjon](https://github.com/sarjon)
* [#9098](https://github.com/PrestaShop/PrestaShop/pull/9098): CO: rename variable $producPropertiesCache (fix typo). Thank you [@anegoda1995](https://github.com/anegoda1995)
* [#9122](https://github.com/PrestaShop/PrestaShop/pull/9122): Add safety returns after ajaxRender calls, by [@jocel1](https://github.com/jocel1)


## Code changes in the '1.7.4.x' branch (for v1.7.4.0)

### Back Office

* [#9028](https://github.com/PrestaShop/PrestaShop/pull/9028): Introduced re-usable authorization system, by [@mickaelandrieu](https://github.com/mickaelandrieu)
* [#9067](https://github.com/PrestaShop/PrestaShop/pull/9067): Refactor Controller class (minor changes). Thank you [@michaelKaefer](https://github.com/michaelKaefer)
* [#9077](https://github.com/PrestaShop/PrestaShop/pull/9077): Update welcome module version, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#9102](https://github.com/PrestaShop/PrestaShop/pull/9102): Update BO theme to Bootstrap 4 final, by [@eternoendless](https://github.com/eternoendless)
* [#9106](https://github.com/PrestaShop/PrestaShop/pull/9106): add a product removal confirmation. Thank you [@khouloudbelguith](https://github.com/khouloudbelguith)
* [#9113](https://github.com/PrestaShop/PrestaShop/pull/9113): Fix wrong css file on BO login page, by [@eternoendless](https://github.com/eternoendless)
* [#9118](https://github.com/PrestaShop/PrestaShop/pull/9118): Fix BO login icons, by [@eternoendless](https://github.com/eternoendless)


### Front Office

* [#9080](https://github.com/PrestaShop/PrestaShop/pull/9080):  Fix Punycode problem when register, by [@PierreRambaud](https://github.com/PierreRambaud)


### Core

* [#9050](https://github.com/PrestaShop/PrestaShop/pull/9050): Fix HookConfigurator: Filter certain non-arrays from theme.yml. Thank you [@jsshandle](https://github.com/jsshandle)
* [#9055](https://github.com/PrestaShop/PrestaShop/pull/9055): The special offers are disappearing suddenly, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#9109](https://github.com/PrestaShop/PrestaShop/pull/9109): 1.7.4.x into develop, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#9115](https://github.com/PrestaShop/PrestaShop/pull/9115): 1.7.4.x into develop, by [@PierreRambaud](https://github.com/PierreRambaud)


## Code changes in the '1.7.3.x' branch (for v1.7.3.3)

### Front Office

* [#9099](https://github.com/PrestaShop/PrestaShop/pull/9099): Follow-up to: display GDPR consent checkbox in contactform. Thank you [@florian-nolte](https://github.com/florian-nolte)
* [#9104](https://github.com/PrestaShop/PrestaShop/pull/9104): Add compliance to GDPR law for ps_emailsubscription module. Thank you [@Joukz](https://github.com/Joukz)


## Code changes in the '1.6.1.x' branch (for v1.6.1.19)

### Front Office

* [#9103](https://github.com/PrestaShop/PrestaShop/pull/9103): Add compliance to GDPR law for blocknewsletter, contact form and mail alerts. Thank you [@Joukz](https://github.com/Joukz)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: @anegoda1995, @florian-nolt, @Joukz, @jsshandle, @khouloudbelguith, @MatthieuMota, @michaelKaefer, @rokaszygmantas, and @sarjon!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with tickets and comments [on the Forge](http://forge.prestashop.com/)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](http://doc.prestashop.com/display/PS16/Contributing+code+to+PrestaShop)
 * [How to write a commit message](http://doc.prestashop.com/display/PS16/How+to+write+a+commit+message)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use the Forge to contribute to PrestaShop](http://doc.prestashop.com/display/PS16/How+to+use+the+Forge+to+contribute+to+PrestaShop). Thank you!

Happy contributin' everyone!

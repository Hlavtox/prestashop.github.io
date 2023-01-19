---
layout: post
aliases: ["/news/coreweekly-week-13-2019"]
title:  "PrestaShop Core Weekly - Week 13 of 2019"
subtitle: "An inside look at the PrestaShop codebase"
date:   2019-04-05 18:00:00
authors: [ AntoineThomas ]
icon: icon-calendar
tags:
 - core-monthly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 25th to Sunday 31st of March 2019.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)


## General messages

Dear Developers,

Code freeze has been postponed to this week because some critical work needed to be finished for the 1.7.6. Stay tuned for an announcement that will provide more information about a possible Alpha release.


## A quick update about PrestaShop's GitHub issues and pull requests:

- [58 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2019-03-25..2019-03-31) have been created in the project repositories;
- [60 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2019-03-25..2019-03-31), including [21 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2019-03-25..2019-03-31) on the core;
- [57 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2019-03-25..2019-03-31) in the project repositories;
- [65 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2019-03-25..2019-03-31), including [55 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2019-03-25..2019-03-31).


## Code changes in the 'develop' branch (for v1.7.6.0)

### Core

* [#11321](https://github.com/PrestaShop/PrestaShop/pull/11321): Translation Manager of Back Office can now manage legacy translations of modules, by [@mickaelandrieu](https://github.com/mickaelandrieu)
* [#11730](https://github.com/PrestaShop/PrestaShop/pull/11730): Use of static instead of ClassName. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11970](https://github.com/PrestaShop/PrestaShop/pull/11970): Unary operator spaces. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11975](https://github.com/PrestaShop/PrestaShop/pull/11975): Space after semicolon. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11977](https://github.com/PrestaShop/PrestaShop/pull/11977): Function declaration. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#12550](https://github.com/PrestaShop/PrestaShop/pull/12550): Improve the way VAT is managed for price calculation. Thank you [@prestamodule](https://github.com/prestamodule)
* [#12967](https://github.com/PrestaShop/PrestaShop/pull/12967): Foward $locale to Translate::getModuleTranslation(), by [@eternoendless](https://github.com/eternoendless)
* [#13008](https://github.com/PrestaShop/PrestaShop/pull/13008): Adds phpdoc on range objectmodel, by [@Matt75](https://github.com/Matt75)
* [#13035](https://github.com/PrestaShop/PrestaShop/pull/13035): Merge 1.7.5.x in develop, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#13057](https://github.com/PrestaShop/PrestaShop/pull/13057): Fixes search action configuration for grids. Thank you [@sarjon](https://github.com/sarjon)


### Back office

* [#12214](https://github.com/PrestaShop/PrestaShop/pull/12214): Migrate "Advanced Parameters > Team > Employees > Add new employee" page. Thank you [@rokaszygmantas](https://github.com/rokaszygmantas)
* [#12523](https://github.com/PrestaShop/PrestaShop/pull/12523): Solved problem with texture upload when attribute has hex color. Thank you [@kpodemski](https://github.com/kpodemski)
* [#12735](https://github.com/PrestaShop/PrestaShop/pull/12735): Brands create/edit migration. Thank you [@zuk3975](https://github.com/zuk3975)
* [#12850](https://github.com/PrestaShop/PrestaShop/pull/12850): [BO] 11692 "Module Manager" tab should be the first tab in Modules Tab. Thank you [@rblaurin](https://github.com/rblaurin)
* [#12914](https://github.com/PrestaShop/PrestaShop/pull/12914): Reduce number of SQL requests to get the employee authorizations, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#12928](https://github.com/PrestaShop/PrestaShop/pull/12928): Manage multi grids on same page, by [@jolelievre](https://github.com/jolelievre)
* [#12981](https://github.com/PrestaShop/PrestaShop/pull/12981): Migration of  "Design -> pages -> cms page listing" . Thank you [@tomas862](https://github.com/tomas862)
* [#13004](https://github.com/PrestaShop/PrestaShop/pull/13004): Integrate new modern theme (compiled from MJML), by [@jolelievre](https://github.com/jolelievre)
* [#13012](https://github.com/PrestaShop/PrestaShop/pull/13012): Update Twig to v1.38, by [@matks](https://github.com/matks)
* [#13014](https://github.com/PrestaShop/PrestaShop/pull/13014): Final Migration of Categories page. Thank you [@sarjon](https://github.com/sarjon)
* [#13043](https://github.com/PrestaShop/PrestaShop/pull/13043): Fix to handle fancybox customer creation in Add an Order page, by [@matks](https://github.com/matks)
* [#13049](https://github.com/PrestaShop/PrestaShop/pull/13049): Fix BO scaling in mobile, by [@eternoendless](https://github.com/eternoendless)
* [#13054](https://github.com/PrestaShop/PrestaShop/pull/13054): Escape all import output data, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#13063](https://github.com/PrestaShop/PrestaShop/pull/13063): Module Manager: Use categoryParentEnglishName instead category name, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#13066](https://github.com/PrestaShop/PrestaShop/pull/13066): Fix npm install not working anymore on new-theme, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#13067](https://github.com/PrestaShop/PrestaShop/pull/13067): Fix manufacturers ns typo's and wrong typecasts in commands. Thank you [@zuk3975](https://github.com/zuk3975)
* [#13076](https://github.com/PrestaShop/PrestaShop/pull/13076): Migrate Add/Edit Profiles page. Thank you [@sarjon](https://github.com/sarjon)
* [#13079](https://github.com/PrestaShop/PrestaShop/pull/13079): Fix visual glitches in new theme, by [@eternoendless](https://github.com/eternoendless)
* [#13094](https://github.com/PrestaShop/PrestaShop/pull/13094): Fix product demo link_rewrite, by [@marionf](https://github.com/marionf)
* [#13095](https://github.com/PrestaShop/PrestaShop/pull/13095): Update dashboard links, by [@eternoendless](https://github.com/eternoendless)
* [#13104](https://github.com/PrestaShop/PrestaShop/pull/13104): Fix bad variable in Customers Add/Edit template, by [@matks](https://github.com/matks)


### Front office

* [#11688](https://github.com/PrestaShop/PrestaShop/pull/11688): Manage catalog mode in list and products page, by [@jolelievre](https://github.com/jolelievre)
* [#12391](https://github.com/PrestaShop/PrestaShop/pull/12391): 12040 broken authentication. Thank you [@arnaudschaeffer](https://github.com/arnaudschaeffer)
* [#12892](https://github.com/PrestaShop/PrestaShop/pull/12892): limit carrier image size on checkout page. Thank you [@YeLnatSs](https://github.com/YeLnatSs)
* [#12893](https://github.com/PrestaShop/PrestaShop/pull/12893): Fix bug on contact for mail too long. Thank you [@YeLnatSs](https://github.com/YeLnatSs)
* [#12964](https://github.com/PrestaShop/PrestaShop/pull/12964): Wrong specific price refresh on product page with combinations, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#13009](https://github.com/PrestaShop/PrestaShop/pull/13009): Change product canonical url to parent, no more redirection, by [@jolelievre](https://github.com/jolelievre)
* [#13081](https://github.com/PrestaShop/PrestaShop/pull/13081): Empty filter should not be shown, by [@PierreRambaud](https://github.com/PierreRambaud)


### Tests

* [#13052](https://github.com/PrestaShop/PrestaShop/pull/13052): Remove usage of TRAVIS_BUILD_DIR, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#13113](https://github.com/PrestaShop/PrestaShop/pull/13113): Fix typo on static, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Installer

* [#13069](https://github.com/PrestaShop/PrestaShop/pull/13069): Update demo features, by [@marionf](https://github.com/marionf)
* [#13078](https://github.com/PrestaShop/PrestaShop/pull/13078): Revert "Delivery slips fails when upgrading to 1.7.5", by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Webservices

* [#12329](https://github.com/PrestaShop/PrestaShop/pull/12329): API and Products: Add missing combination IDs in the pack content, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)



## Code changes in modules, themes & tools

### Circuit breaker

* [#29](https://github.com/PrestaShop/circuit-breaker/pull/29): Downgrade Guzzle to v5, by [@eternoendless](https://github.com/eternoendless)
* [#30](https://github.com/PrestaShop/circuit-breaker/pull/30): Merge version 2.0.0, by [@eternoendless](https://github.com/eternoendless)


### Auto upgrade

* [#293](https://github.com/PrestaShop/autoupgrade/pull/293): Call CLDR update only if the class exists, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Docker

* [#156](https://github.com/PrestaShop/docker/pull/156): Remove builds with PHP 5.5, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#159](https://github.com/PrestaShop/docker/pull/159): Defines only made on true values, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### UI Kit

* [#63](https://github.com/PrestaShop/prestashop-ui-kit/pull/63): Use pixel-based breakpoints once again, by [@eternoendless](https://github.com/eternoendless)


### MBO

* [#87](https://github.com/PrestaShop/ps_mbo/pull/87): Make MBO handle adding the Recommended modules button in pages, by [@eternoendless](https://github.com/eternoendless)


### NVD3 Charts

* [#4](https://github.com/PrestaShop/graphnvd3/pull/4): Remove die() from the module, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#5](https://github.com/PrestaShop/graphnvd3/pull/5): Bump version to 2.0.1, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Shop Generator

* [#3](https://github.com/PrestaShop/prestashop-shop-creator/pull/3): add composer.lock and ignore config.yml + generated_data directory, by [@PierreRambaud](https://github.com/PierreRambaud)


### Main Menu

* [#20](https://github.com/PrestaShop/ps_mainmenu/pull/20): Fix boom-3633, by [@marionf](https://github.com/marionf)


## Changes in Documentation

* [#223](https://github.com/PrestaShop/docs/pull/223): Added docs on Grid templating customization, by [@mickaelandrieu](https://github.com/mickaelandrieu)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: @arnaudschaeffe, @kpodemski, @MathiasReker, @prestamodule, @rblaurin, @rokaszygmantas, @sarjon, @tomas862, @YeLnatSs, @zuk3975!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

---
layout: post
aliases: ["/news/coreweekly-week-05-2019"]
title:  "PrestaShop Core Weekly - Week 05 of 2019"
subtitle: "An inside look at the PrestaShop codebase"
date:   2019-02-04 16:30:00
authors: [ AntoineThomas ]
icon: icon-calendar
tags:
 - core-monthly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 28th of January to Sunday 03rd of February 2019.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)


## General messages

Dear Developers,

Previous weeks, many pull requests have been merged to prepare an update for PrestaShop 1.7.5. Just have a look at the [PrestaShop 1.7.5.1 milestone on GitHub](https://github.com/PrestaShop/PrestaShop/milestones/1.7.5.1): there are only 3 issues and 3 pull requests left, and it will possible to build it.

If you read this core weekly until the bottom, you will also notice that the code lint done on the Auto-upgrade module has been merged.


## A quick update about PrestaShop's GitHub issues and pull requests:

- [67 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2019-01-28..2019-02-03) have been created in the project repositories
- [52 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2019-01-28..2019-02-03), including [10 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2019-01-28..2019-02-03) on the core.
- [55 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2019-01-28..2019-02-03) in the project repositories
- [73 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2019-01-28..2019-02-03), including [54 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2019-01-28..2019-02-03)

## Code changes in the 'develop' branch (for v1.7.6.0)

### Core

* [#10783](https://github.com/PrestaShop/PrestaShop/pull/10783): Migration of Advanced Parameters > Team > Profiles page.. Thank you [@rokaszygmantas](https://github.com/rokaszygmantas)
* [#11442](https://github.com/PrestaShop/PrestaShop/pull/11442): Fixed the problem with the type of a return value in Module::onInstall(). Thank you [@zapalm](https://github.com/zapalm)
* [#11968](https://github.com/PrestaShop/PrestaShop/pull/11968): Switch case space. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#11997](https://github.com/PrestaShop/PrestaShop/pull/11997): Happy new year 2019, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#12208](https://github.com/PrestaShop/PrestaShop/pull/12208): Add filter on the modules folder to avoid caching all files by Twig, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#12344](https://github.com/PrestaShop/PrestaShop/pull/12344): Fix translation on account creation email error. Thank you [@SebBareyre](https://github.com/SebBareyre)


### Back office

* [#8993](https://github.com/PrestaShop/PrestaShop/pull/8993): Fix HTML formated configuration not saved. Thank you [@shaffe-fr](https://github.com/shaffe-fr)
* [#10911](https://github.com/PrestaShop/PrestaShop/pull/10911): Build new theme using Webpack 4. Thank you [@CaptainYouz](https://github.com/CaptainYouz)
* [#11175](https://github.com/PrestaShop/PrestaShop/pull/11175): Update AdminProductsController.php. Thank you [@simondaigre](https://github.com/simondaigre)
* [#12316](https://github.com/PrestaShop/PrestaShop/pull/12316): Access rules for SystemInformationController and MemcacheServer, by [@matks](https://github.com/matks)


### Front office

* [#12341](https://github.com/PrestaShop/PrestaShop/pull/12341): Use show_price to display price in schema.org tags. Thank you [@arnaudschaeffer](https://github.com/arnaudschaeffer)


### Webservices

* [#12201](https://github.com/PrestaShop/PrestaShop/pull/12201): Fixes sql exception when creating a product_option without values. Thank you [@mowcixo](https://github.com/mowcixo)


### Tests

* [#12304](https://github.com/PrestaShop/PrestaShop/pull/12304): Add unit tests for Core IdentifiableObject classes, by [@matks](https://github.com/matks)
* [#12315](https://github.com/PrestaShop/PrestaShop/pull/12315): Create order as a guest test and update readme file. Thank you [@YosraAk](https://github.com/YosraAk)
* [#12317](https://github.com/PrestaShop/PrestaShop/pull/12317): Create order in BO test. Thank you [@ansar21mallouli](https://github.com/ansar21mallouli)
* [#12327](https://github.com/PrestaShop/PrestaShop/pull/12327): Add SEO options especially for product attributes in title, the front…, by [@jolelievre](https://github.com/jolelievre)
* [#12343](https://github.com/PrestaShop/PrestaShop/pull/12343): Print invoice order. Thank you [@ansar21mallouli](https://github.com/ansar21mallouli)
* [#12351](https://github.com/PrestaShop/PrestaShop/pull/12351): Update create order in FO test. Thank you [@YosraAk](https://github.com/YosraAk)
* [#12355](https://github.com/PrestaShop/PrestaShop/pull/12355): Print the delivery slip. Thank you [@ansar21mallouli](https://github.com/ansar21mallouli)
* [#12362](https://github.com/PrestaShop/PrestaShop/pull/12362): Go to next and previous page test. Thank you [@ansar21mallouli](https://github.com/ansar21mallouli)
* [#12369](https://github.com/PrestaShop/PrestaShop/pull/12369): Fix deprecation notices reported by Composer, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#12378](https://github.com/PrestaShop/PrestaShop/pull/12378): Improve report files generation, by [@PierreRambaud](https://github.com/PierreRambaud)


## Code changes in the '1.7.5.x' branch (for v1.7.5.1)

### Core

* [#12354](https://github.com/PrestaShop/PrestaShop/pull/12354): Fix cancel button on Safari browser, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Back Office

* [#12205](https://github.com/PrestaShop/PrestaShop/pull/12205): Bulk module action, by [@jolelievre](https://github.com/jolelievre)
* [#12361](https://github.com/PrestaShop/PrestaShop/pull/12361): Refacto SearchParameters and SearchParametersResolver for pagination, by [@jolelievre](https://github.com/jolelievre)
* [#12395](https://github.com/PrestaShop/PrestaShop/pull/12395): Change stock alert z index to be on top of header, by [@jolelievre](https://github.com/jolelievre)


## Code changes in modules, themes & tools


###  Auto-upgrade

* [#235](https://github.com/PrestaShop/autoupgrade/pull/235): Fix php docs and comments. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#236](https://github.com/PrestaShop/autoupgrade/pull/236): Array indentation. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#238](https://github.com/PrestaShop/autoupgrade/pull/238): Combine consecutive issets. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#239](https://github.com/PrestaShop/autoupgrade/pull/239): Logical operators. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#243](https://github.com/PrestaShop/autoupgrade/pull/243): Is null. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#245](https://github.com/PrestaShop/autoupgrade/pull/245): Php unit dedicate assert. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#246](https://github.com/PrestaShop/autoupgrade/pull/246): Use PhpUnit assertTrue / assertFalse. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#247](https://github.com/PrestaShop/autoupgrade/pull/247): Php unit set up tear down visibility. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#248](https://github.com/PrestaShop/autoupgrade/pull/248): Php unit strict. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#249](https://github.com/PrestaShop/autoupgrade/pull/249): No null property initialization. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#252](https://github.com/PrestaShop/autoupgrade/pull/252): Function to constant. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#253](https://github.com/PrestaShop/autoupgrade/pull/253): Improve type casting. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#254](https://github.com/PrestaShop/autoupgrade/pull/254): Concat space. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#260](https://github.com/PrestaShop/autoupgrade/pull/260): Multiline whitespace before semicolons. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#261](https://github.com/PrestaShop/autoupgrade/pull/261): Method chaining indentation. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#262](https://github.com/PrestaShop/autoupgrade/pull/262): Blank lines. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#263](https://github.com/PrestaShop/autoupgrade/pull/263): Random api migration. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#265](https://github.com/PrestaShop/autoupgrade/pull/265): Butify yml files. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#268](https://github.com/PrestaShop/autoupgrade/pull/268): lossless compression. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#274](https://github.com/PrestaShop/autoupgrade/pull/274): Handle PrestaShop version in AppKernel, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Mail alerts

* [#14](https://github.com/PrestaShop/ps_emailalerts/pull/14): Do not stop execution if mail send failed, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#15](https://github.com/PrestaShop/ps_emailalerts/pull/15): Deploy v2.1.1 of ps_emailalerts, by [@matks](https://github.com/matks)


### Link list

* [#45](https://github.com/PrestaShop/ps_linklist/pull/45): Corection wrong working as widget. Thank you [@mbareja](https://github.com/mbareja)


### Docker Internal Images

* [#23](https://github.com/PrestaShop/docker-internal-images/pull/23): Increase upload size to 40M, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


## Changes in Documentation

* [#190](https://github.com/PrestaShop/docs/pull/190): Update overrides.md. Thank you [@Sahnounmannaii](https://github.com/Sahnounmannaii)
* [#191](https://github.com/PrestaShop/docs/pull/191): Webservice doc, by [@jolelievre](https://github.com/jolelievre)
* [#192](https://github.com/PrestaShop/docs/pull/192): Added a section for testing when they migrate a page, by [@mickaelandrieu](https://github.com/mickaelandrieu)
* [#197](https://github.com/PrestaShop/docs/pull/197): duplicate word. Thank you [@vhessam](https://github.com/vhessam)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: @ansar21mallouli, @arnaudschaeffer, @CaptainYouz, @MathiasReker, @mbareja, @mowcixo, @rokaszygmantas, @SebBareyre, @shaffe-fr, @Sahnounmannaii, @simondaigre, @vhessam, @YosraAk, @zapalm!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

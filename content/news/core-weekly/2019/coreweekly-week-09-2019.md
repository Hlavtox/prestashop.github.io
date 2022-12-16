---
layout: post
aliases: ["/news/coreweekly-week-09-2019"]
title:  "PrestaShop Core Weekly - Week 09 of 2019"
subtitle: "An inside look at the PrestaShop codebase"
date:   2019-03-08 11:00:00
authors: [ AntoineThomas ]
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 25th of February to Sunday 03rd of March 2019.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)


## General messages

Dear Developers,

It seems that we eventually found a proofreader for the devdocs ;-)

That is a very interesting kind of contribution: this is something that does not require coding skills, but this is still very valuable. The documentation is then more pleasant to read and to understand.

There are many activities that you can do if you want to help with the PrestaShop open source project, but you are not a developer:

- Telling that it's great and recommanding it
- Planning events
- Writings documentation and tutorials, or producing videos to show how it works
- Helping with issue sorting, like for example identifying duplicates or asking for details
- Helping users on the forums and other websites were users ask question about the software


## A quick update about PrestaShop's GitHub issues and pull requests:

- [55 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2019-02-25..2019-03-03) have been created in the project repositories;
()
- [53 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2019-02-25..2019-03-03), including [5 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2019-02-25..2019-03-03) on the core;
- [59 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2019-02-25..2019-03-03) in the project repositories;
()
- [48 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2019-02-25..2019-03-03), including [35 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2019-02-25..2019-03-03).

## Code changes in the 'develop' branch (for v1.7.6.0)

### Core

* [#12346](https://github.com/PrestaShop/PrestaShop/pull/12346): Add Category form builder & handler. Thank you [@sarjon](https://github.com/sarjon)
* [#12498](https://github.com/PrestaShop/PrestaShop/pull/12498): Add showcase card for Suppliers list. Thank you [@sarjon](https://github.com/sarjon)
* [#12739](https://github.com/PrestaShop/PrestaShop/pull/12739): Revert to Webpack 2, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#12756](https://github.com/PrestaShop/PrestaShop/pull/12756): CO: Fix bug when create class override Address. Thank you [@dariusakafest](https://github.com/dariusakafest)
* [#12758](https://github.com/PrestaShop/PrestaShop/pull/12758): Added a Theme Enabler command, by [@mickaelandrieu](https://github.com/mickaelandrieu)


### Back office

* [#10595](https://github.com/PrestaShop/PrestaShop/pull/10595): Migration of "Shop parameters >Traffic & SEO > SEO & URL > Add new / edit page" form. Thank you [@tomas862](https://github.com/tomas862)
* [#12622](https://github.com/PrestaShop/PrestaShop/pull/12622): Refactor AddonsStoreController to use annotations and some improvements, by [@matks](https://github.com/matks)
* [#12668](https://github.com/PrestaShop/PrestaShop/pull/12668): Fix help sidebar when adding/editing language. Thank you [@sarjon](https://github.com/sarjon)
* [#12706](https://github.com/PrestaShop/PrestaShop/pull/12706): Kpis list are now customizables using hooks, by [@mickaelandrieu](https://github.com/mickaelandrieu)
* [#12709](https://github.com/PrestaShop/PrestaShop/pull/12709): Refactor MetaController to secure search usage, by [@matks](https://github.com/matks)
* [#12711](https://github.com/PrestaShop/PrestaShop/pull/12711): BO the shipping cost becomes free if more than a half ordered. Thank you [@LedCloud](https://github.com/LedCloud)
* [#12713](https://github.com/PrestaShop/PrestaShop/pull/12713): Enable usage of roles for Module Updates and Module Alerts pages and manage access, by [@matks](https://github.com/matks)
* [#12716](https://github.com/PrestaShop/PrestaShop/pull/12716): Prevent including jQuery in the new theme, by [@eternoendless](https://github.com/eternoendless)
* [#12723](https://github.com/PrestaShop/PrestaShop/pull/12723): Patch to Issue #12500. Thank you [@rblaurin](https://github.com/rblaurin)
* [#12761](https://github.com/PrestaShop/PrestaShop/pull/12761): BO: Remove timeout from product image upload. Thank you [@JohnMidity](https://github.com/JohnMidity)


### Front office

* [#12696](https://github.com/PrestaShop/PrestaShop/pull/12696): fix missing coma in sql upgrade file, by [@tomlev](https://github.com/tomlev)
* [#12733](https://github.com/PrestaShop/PrestaShop/pull/12733): Changed the regex to force space and hyphen in postcode validation. Thank you [@jojotjebaby](https://github.com/jojotjebaby)


### Localization pack

* [#12747](https://github.com/PrestaShop/PrestaShop/pull/12747): Fix PhpDoc for AttributeGroupCore::getAttributes(). Thank you [@BadPixxel](https://github.com/BadPixxel)


### Tests

* [#12488](https://github.com/PrestaShop/PrestaShop/pull/12488): Add a descriptif comment for the broken test "create_edit_delete_language". Thank you [@YosraAk](https://github.com/YosraAk)
* [#12490](https://github.com/PrestaShop/PrestaShop/pull/12490): TE: add a descriptif comment for the broken test "create_edit_delete_contact". Thank you [@YosraAk](https://github.com/YosraAk)
* [#12495](https://github.com/PrestaShop/PrestaShop/pull/12495): Add a descriptif comment for the broken test "installation language <> country ". Thank you [@YosraAk](https://github.com/YosraAk)
* [#12678](https://github.com/PrestaShop/PrestaShop/pull/12678): Create virtual product. Thank you [@ansar21mallouli](https://github.com/ansar21mallouli)
* [#12679](https://github.com/PrestaShop/PrestaShop/pull/12679): Add some fixes to the campaign full. Thank you [@YosraAk](https://github.com/YosraAk)


## Code changes in modules, themes & tools

### Nightly Board

* [#2](https://github.com/PrestaShop/nightly-board/pull/2): Create LICENSE, by [@PierreRambaud](https://github.com/PierreRambaud)


### Mail alerts

* [#18](https://github.com/PrestaShop/ps_emailalerts/pull/18): php 7.2 compatibility fix. Thank you [@kpodemski](https://github.com/kpodemski)


### Gammification

* [#62](https://github.com/PrestaShop/gamification/pull/62): Stop including jQuery twice in 1.7, by [@eternoendless](https://github.com/eternoendless)


## Changes in Documentation

* [#213](https://github.com/PrestaShop/docs/pull/213): Minor grammar corrections. Thank you [@d-roduit](https://github.com/d-roduit)
* [#214](https://github.com/PrestaShop/docs/pull/214): Minor grammar correction. Thank you [@d-roduit](https://github.com/d-roduit)
* [#215](https://github.com/PrestaShop/docs/pull/215): Minor Grammar Corrections. Thank you [@d-roduit](https://github.com/d-roduit)
* [#216](https://github.com/PrestaShop/docs/pull/216): Moved PrestaShop webservices outside of Components section, by [@mickaelandrieu](https://github.com/mickaelandrieu)
* [#217](https://github.com/PrestaShop/docs/pull/217): Grammar + consistency corrections. Thank you [@d-roduit](https://github.com/d-roduit)
* [#218](https://github.com/PrestaShop/docs/pull/218): Minor orthographic corrections. Thank you [@d-roduit](https://github.com/d-roduit)
* [#219](https://github.com/PrestaShop/docs/pull/219): Grammar corrections. Thank you [@d-roduit](https://github.com/d-roduit)
* [#220](https://github.com/PrestaShop/docs/pull/220): Spelling corrections. Thank you [@d-roduit](https://github.com/d-roduit)
* [#221](https://github.com/PrestaShop/docs/pull/221): Update back-office.md. Thank you [@arthtux](https://github.com/arthtux)

<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: @ansar21mallouli, @arthtux, @BadPixxel, @d-roduit, @dariusakafest, @JohnMidity, @jojotjebaby, @kpodemski, @LedCloud, @rblaurin, @sarjon, @tomas862, @YosraAk!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

---
layout: post
aliases: ["/news/coreweekly-week-03-2020"]
title:  "PrestaShop Core Weekly - Week 3 of 2020"
subtitle: "An inside look at the PrestaShop codebase"
date:   2020-01-23
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
icon: icon-calendar
tags:
 - core-monthly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 13th to Sunday 19th of January 2020.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)

## General messages

Dear Developers,

There is a lot of things going on this week !

The first one is obviously about PrestaShop 1.7.6.3 being available. This maintenance release fixes 16 issues reported on versions 1.7.6.0, 1.7.6.1 and 1.7.6.2. Please [read the release note](https://build.prestashop.com/news/prestashop-1-7-6-3-maintenance-release/) for more informations.

Secondly, we have created the `1.7.7.x` branch which will carry the changes being released with 1.7.7.0. So from now on, the work carried out on `develop` branch will be released with 1.7.8.

Finally, after asking you what was your opinion about [no longer committing generated files](https://build.prestashop.com/news/open-question-not-commiting-assets-anymore/) and receiving positive feedback for the change, we have implemented it into the [develop branch](https://github.com/PrestaShop/PrestaShop/pull/16670). We have also [updated the developer documentation](https://github.com/PrestaShop/docs/pull/418) accordingly in order to provide developers with all the necessary information to be able to generate these files on their own.

## A quick update about PrestaShop's GitHub issues and pull requests:

- [73 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2020-01-13..2020-01-19) have been created in the project repositories;
- [48 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2020-01-13..2020-01-19), including [9 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2020-01-13..2020-01-19) on the core;
- [66 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2020-01-13..2020-01-19) in the project repositories;
- [71 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2020-01-13..2020-01-19), including [41 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2020-01-13..2020-01-19).


## Code changes in the 'develop' branch


### Core
* [#17204](https://github.com/PrestaShop/PrestaShop/pull/17204): Add missing deprecation on previous PerformanceFormHandler, by [@matks](https://github.com/matks)


### Back office
* [#17132](https://github.com/PrestaShop/PrestaShop/pull/17132): Javascript errors in BO's webservice and login page, by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#16964](https://github.com/PrestaShop/PrestaShop/pull/16964): Refactor UI kit form theme and apply it to the Performance page, by [@eternoendless](https://github.com/eternoendless)
* [#16961](https://github.com/PrestaShop/PrestaShop/pull/16961): Remove useless customer query filter statements, by [@matks](https://github.com/matks)


### Front office
* [#16956](https://github.com/PrestaShop/PrestaShop/pull/16956): Changing classic theme filters alignments and spaces, by [@NeOMakinG](https://github.com/NeOMakinG)


### Installer
* [#17100](https://github.com/PrestaShop/PrestaShop/pull/17100): Update the number of PrestaShop stores, by [@LouiseBonnard](https://github.com/LouiseBonnard)


### Tests
* [#17183](https://github.com/PrestaShop/PrestaShop/pull/17183): Sanity tests - Fix CRUD standard product with combinations test . Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#17150](https://github.com/PrestaShop/PrestaShop/pull/17150): Functional tests - Fix disable shop function, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#17129](https://github.com/PrestaShop/PrestaShop/pull/17129): Functional tests - Set FR text value for custom maintenance text. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#17086](https://github.com/PrestaShop/PrestaShop/pull/17086): Functional tests - Crud customer address. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#17028](https://github.com/PrestaShop/PrestaShop/pull/17028): Behat tests for Customer, Address features handlers. Thank you [@tdavidsonas88](https://github.com/tdavidsonas88)
* [#15431](https://github.com/PrestaShop/PrestaShop/pull/15431): Add Money unit test, by [@matks](https://github.com/matks)


### Merge
* [#17221](https://github.com/PrestaShop/PrestaShop/pull/17221): Merge 1.7.7.x into develop - 17/01/2020, by [@matks](https://github.com/matks)
* [#17192](https://github.com/PrestaShop/PrestaShop/pull/17192): Merge 1.7.7.x into develop - 15/01/2020 - again, by [@matks](https://github.com/matks)
* [#17184](https://github.com/PrestaShop/PrestaShop/pull/17184): Merge 1.7.7.x into develop - 15/01/2020 , by [@PierreRambaud](https://github.com/PierreRambaud)


## Code changes in the '1.7.7.x' branch (for v1.7.7.0)


### Core
* [#13761](https://github.com/PrestaShop/PrestaShop/pull/13761): Add compatibility with PHP 7.3, by [@mickaelandrieu](https://github.com/mickaelandrieu)


### Back office
* [#17229](https://github.com/PrestaShop/PrestaShop/pull/17229): Recompute FOSJSRouting JSON file, by [@matks](https://github.com/matks)
* [#17175](https://github.com/PrestaShop/PrestaShop/pull/17175): Replace partialRefund form/builder/dataProvider with CancelProduct, by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#17169](https://github.com/PrestaShop/PrestaShop/pull/17169): Refacto partial refund handler, by [@jolelievre](https://github.com/jolelievre)


### Tests
* [#17202](https://github.com/PrestaShop/PrestaShop/pull/17202): Functional tests - Add numbers for all directories. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#17201](https://github.com/PrestaShop/PrestaShop/pull/17201): Functional Tests - Fix "emailThemes/01_previewEmailThemes" test. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#17168](https://github.com/PrestaShop/PrestaShop/pull/17168): Functional tests - Fix test customer bulk action, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#17167](https://github.com/PrestaShop/PrestaShop/pull/17167): Functional Tests - Fix Enable Disable shop automated test, by [@SimonGrn](https://github.com/SimonGrn)
* [#17155](https://github.com/PrestaShop/PrestaShop/pull/17155): Refacto refund, by [@jolelievre](https://github.com/jolelievre)
* [#17154](https://github.com/PrestaShop/PrestaShop/pull/17154): Functional tests - Fix test employee and maintenance, by [@boubkerbribri](https://github.com/boubkerbribri)


### Merge
* [#17186](https://github.com/PrestaShop/PrestaShop/pull/17186): Merge 1.7.6.x into 1.7.7.x - 11/01/2020 , by [@matks](https://github.com/matks)


## Code changes in the '1.7.6.x' branch (for v1.7.6.3)


### Core
* [#17130](https://github.com/PrestaShop/PrestaShop/pull/17130): Make $localizedSymbols variable to be compatible with develop, by [@atomiix](https://github.com/atomiix)


### Back office
* [#16906](https://github.com/PrestaShop/PrestaShop/pull/16906): Handle profile name above 32 chars exception, by [@atomiix](https://github.com/atomiix)


## Code changes in modules, themes & tools


### Changes in developer documentation
* [#444](https://github.com/PrestaShop/docs/pull/444): Add link to "why github flow is complex" article, by [@matks](https://github.com/matks)
* [#443](https://github.com/PrestaShop/docs/pull/443): Add MySQL default credentials. Thank you [@gadnis](https://github.com/gadnis)
* [#442](https://github.com/PrestaShop/docs/pull/442): Fix typo in tabs.md, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#440](https://github.com/PrestaShop/docs/pull/440): Provide github tuto links to contribute, by [@matks](https://github.com/matks)


### PrestaShop Specifications
* [#80](https://github.com/PrestaShop/prestashop-specs/pull/80): Clean and complete the README. Thank you [@sam-pires](https://github.com/sam-pires)


### Core Weekly Generator tool
* [#22](https://github.com/PrestaShop/core-weekly-generator/pull/22): Some updates for the Core Weekly template, by [@matks](https://github.com/matks)


### Faceted search module
* [#155](https://github.com/PrestaShop/ps_facetedsearch/pull/155): Bump npm packages, by [@PierreRambaud](https://github.com/PierreRambaud)


### Prestashop UI Kit
* [#84](https://github.com/PrestaShop/prestashop-ui-kit/pull/84): Improve Inputs, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#76](https://github.com/PrestaShop/prestashop-ui-kit/pull/76): Improve cards, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#71](https://github.com/PrestaShop/prestashop-ui-kit/pull/71): Add default ps-dropdown and adjust other dropdown elements, by [@NeOMakinG](https://github.com/NeOMakinG)


### MBO Module
* [#93](https://github.com/PrestaShop/ps_mbo/pull/93): Add missing domains and improve wordings, by [@LouiseBonnard](https://github.com/LouiseBonnard)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@matks](https://github.com/matks), [@SimonGrn](https://github.com/SimonGrn), [@nesrineabdmouleh](https://github.com/nesrineabdmouleh), [@PierreRambaud](https://github.com/PierreRambaud), [@matthieu-rolland](https://github.com/matthieu-rolland), [@sam-pires](https://github.com/sam-pires), [@jolelievre](https://github.com/jolelievre), [@boubkerbribri](https://github.com/boubkerbribri), [@gadnis](https://github.com/gadnis), [@Quetzacoalt91](https://github.com/Quetzacoalt91), [@atomiix](https://github.com/atomiix), [@LouiseBonnard](https://github.com/LouiseBonnard), [@tdavidsonas88](https://github.com/tdavidsonas88), [@eternoendless](https://github.com/eternoendless), [@NeOMakinG](https://github.com/NeOMakinG), [@mickaelandrieu](https://github.com/mickaelandrieu)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

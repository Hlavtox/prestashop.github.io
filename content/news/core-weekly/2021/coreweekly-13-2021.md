---
layout: post
aliases: ["/news/coreweekly-13-2021"]
slug: "coreweekly-13-2021"
title:  "PrestaShop Core Weekly - Week 13 of 2021"
subtitle: "An inside look at the PrestaShop codebase"
date:   2021-04-06
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
twitter_image: /assets/images/theme/banner-core-weekly.jpg
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 29th of March to Sunday 4th of April 2021.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)

## General messages

Dear developers,

Last week was filled with lot of interesting events!

First, [PrestaShop 1.7.7.3](https://build.prestashop.com/news/prestashop-1-7-7-3-maintenance-release/) was released on the 30st of March, 2021. This maintenance release fixes 10 bugs reported on previous 1.7.7 versions, as well as one security issue.

On the 31st of March, the maintainers team held again a video conferencing for the project public demonstrations session, streamed live on [YouTube](https://youtu.be/UJ_XQs8trs4).

Two achievements were presented:
- 1.7.8 Feature Flags by [@matks](http://github.com/matks)
- Backlog cleaning by [@hibatallahAouadni](http://github.com/hibatallahAouadni)

A complete summary of the session will soon be published.

Another repository was granted a security maintenance release: [ps_emailsubscription v2.6.1](https://github.com/PrestaShop/ps_emailsubscription/releases/tag/v2.6.1).

Finally, we have entered the month of April which is the month where PrestaShop 1.7.8 should be [feature frozen](https://build.prestashop.com/news/ps17-minor-release-lifecycle/#feature-freeze). The very last Pull Requests are being submitted and validated so we can complete the 1.7.8 milestone. Needless to say, maintainers are very busy at this moment! :muscle:


## Releases

* [PrestaShop](https://github.com/PrestaShop/PrestaShop) [1.7.7.3](https://github.com/PrestaShop/PrestaShop/releases/tag/1.7.7.3)
* [ps_sharebuttons](https://github.com/PrestaShop/ps_sharebuttons) module: [v2.1.1](https://github.com/PrestaShop/ps_sharebuttons/releases/tag/v2.1.1)
* [ps_emailsubscription](https://github.com/PrestaShop/ps_emailsubscription) module: [v2.6.1](https://github.com/PrestaShop/ps_emailsubscription/releases/tag/v2.6.1)
* [ps_emailalerts](https://github.com/PrestaShop/ps_emailalerts) module: [v2.3.0](https://github.com/PrestaShop/ps_emailalerts/releases/tag/v2.3.0)


## A quick update about PrestaShop's GitHub issues and pull requests:

- [52 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2021-03-29..2021-04-04) have been created in the project repositories;
- [45 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2021-03-29..2021-04-04), including [16 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2021-03-29..2021-04-04) on the core;
- [91 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2021-03-29..2021-04-04) in the project repositories;
- [102 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2021-03-29..2021-04-04), including [88 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2021-03-29..2021-04-04).



## Code changes in the 'develop' branch


### Core
* [#23797](https://github.com/PrestaShop/PrestaShop/pull/23797): Updated JS Routing file. Thank you [@github-actions[bot]](https://github.com/apps/github-actions)
* [#23789](https://github.com/PrestaShop/PrestaShop/pull/23789): Fix `Validate::isArrayWithIds` method issue. Thank you [@PululuK](https://github.com/PululuK)
* [#22290](https://github.com/PrestaShop/PrestaShop/pull/22290): Simplify product isNew() query. Thank you [@davidglezz](https://github.com/davidglezz)
* [#22152](https://github.com/PrestaShop/PrestaShop/pull/22152): No unit of value for the txt files attached to a product. Thank you [@PululuK](https://github.com/PululuK)


### Back office
* [#23844](https://github.com/PrestaShop/PrestaShop/pull/23844): Fix BOEvent not being on window object anymore, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#23840](https://github.com/PrestaShop/PrestaShop/pull/23840): Disable shop context switching from the multistore header if the shop has no URL, by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#23818](https://github.com/PrestaShop/PrestaShop/pull/23818): Fixed legacy "view my shop" link when multistore is not used, by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#23811](https://github.com/PrestaShop/PrestaShop/pull/23811): Remove instock. Thank you [@WebHelpersPau](https://github.com/WebHelpersPau)
* [#23727](https://github.com/PrestaShop/PrestaShop/pull/23727): Add filtering and sorting to combination list. Thank you [@zuk3975](https://github.com/zuk3975)
* [#23675](https://github.com/PrestaShop/PrestaShop/pull/23675): Add remove feature on product page v2, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#23599](https://github.com/PrestaShop/PrestaShop/pull/23599): Fix module page responsive bug on modal nav, close icon and icon height, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#23583](https://github.com/PrestaShop/PrestaShop/pull/23583): Remove unused bootstrap classes causing side effects on nav, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#23579](https://github.com/PrestaShop/PrestaShop/pull/23579): Remove useless code since migration to BO new-theme. Thank you [@e-gaulue](https://github.com/e-gaulue)
* [#23298](https://github.com/PrestaShop/PrestaShop/pull/23298): Add TinyMCE mobile theme in the BO, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#23232](https://github.com/PrestaShop/PrestaShop/pull/23232): Add custom tinymce configuration on migrated pages, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#22999](https://github.com/PrestaShop/PrestaShop/pull/22999): Add eslint on the default BO theme, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#21652](https://github.com/PrestaShop/PrestaShop/pull/21652): Simplify database settings, DB Backup and add new database query forms. Thank you [@JevgenijVisockij](https://github.com/JevgenijVisockij)
* [#20370](https://github.com/PrestaShop/PrestaShop/pull/20370): Migrate "Improve > International > Locations > Zones" and create/edit of zones. Thank you [@ks129](https://github.com/ks129)


### Front office
* [#23841](https://github.com/PrestaShop/PrestaShop/pull/23841): Fix autocomplete UI going under the header on classic theme, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#23528](https://github.com/PrestaShop/PrestaShop/pull/23528): Fix, hide desactivated  categories in breadcrumbs. Thank you [@mkdgs](https://github.com/mkdgs)
* [#20929](https://github.com/PrestaShop/PrestaShop/pull/20929): Avoid loading all combinations in memory when only one is needed. Thank you [@jbenezech](https://github.com/jbenezech)


### Tests
* [#23861](https://github.com/PrestaShop/PrestaShop/pull/23861): Split sanity workflow matrix into four workflows, by [@jolelievre](https://github.com/jolelievre)
* [#23855](https://github.com/PrestaShop/PrestaShop/pull/23855): Fix Close onboarding on sanity tests, by [@boubkerbribri](https://github.com/boubkerbribri)


## Code changes in the '1.7.7.x' branch


### Back office
* [#23691](https://github.com/PrestaShop/PrestaShop/pull/23691): Fix notification refresh on migrated pages, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#22228](https://github.com/PrestaShop/PrestaShop/pull/22228): Fixed Update Quantity in an order in multishop context, by [@Progi1984](https://github.com/Progi1984)


### Front office
* [#23802](https://github.com/PrestaShop/PrestaShop/pull/23802): Fix jquery selector warning with ps_currencyselector, by [@NeOMakinG](https://github.com/NeOMakinG)


### Tests
* [#23852](https://github.com/PrestaShop/PrestaShop/pull/23852): Fix 'Add to cart' test, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#23792](https://github.com/PrestaShop/PrestaShop/pull/23792): Fix enable demo mode on dashboard and trim the message set on contact us page, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#23780](https://github.com/PrestaShop/PrestaShop/pull/23780): Delete unused functions on common page, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#23778](https://github.com/PrestaShop/PrestaShop/pull/23778): Wrap playwright function waitForSelector, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#23736](https://github.com/PrestaShop/PrestaShop/pull/23736): Add test 'Send a message with an ordered product'. Thank you [@RomainBocheux](https://github.com/RomainBocheux)


## Code changes in modules, themes & tools


### Gamification module
* [#80](https://github.com/PrestaShop/gamification/pull/80): Bump symfony/phpunit-bridge from 3.4.47 to 5.2.6. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#79](https://github.com/PrestaShop/gamification/pull/79): Improve project, by [@Progi1984](https://github.com/Progi1984)


### Language selector module
* [#23](https://github.com/PrestaShop/ps_languageselector/pull/23): Migrated from Travis CI to Github Actions, by [@Progi1984](https://github.com/Progi1984)


### Featured products module
* [#37](https://github.com/PrestaShop/ps_featuredproducts/pull/37): Migrated from Travis CI to Github Actions, by [@Progi1984](https://github.com/Progi1984)


### Customer reassurance block module
* [#165](https://github.com/PrestaShop/blockreassurance/pull/165): Bump webpack from 5.28.0 to 5.30.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#164](https://github.com/PrestaShop/blockreassurance/pull/164): Bump y18n from 4.0.0 to 4.0.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#163](https://github.com/PrestaShop/blockreassurance/pull/163): Bump @babel/core from 7.13.13 to 7.13.14. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#162](https://github.com/PrestaShop/blockreassurance/pull/162): Bump eslint-config-prestashop version to 0.1.0, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#161](https://github.com/PrestaShop/blockreassurance/pull/161): Bump mini-css-extract-plugin from 1.3.9 to 1.4.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#159](https://github.com/PrestaShop/blockreassurance/pull/159): Bump webpack-cli from 4.5.0 to 4.6.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#158](https://github.com/PrestaShop/blockreassurance/pull/158): Bump @babel/core from 7.13.10 to 7.13.13. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#157](https://github.com/PrestaShop/blockreassurance/pull/157): Bump prestashop/php-dev-tools from 3.10 to 3.15. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Faceted search module
* [#393](https://github.com/PrestaShop/ps_facetedsearch/pull/393): Bump webpack from 5.28.0 to 5.30.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#392](https://github.com/PrestaShop/ps_facetedsearch/pull/392): Bump y18n from 4.0.0 to 4.0.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#391](https://github.com/PrestaShop/ps_facetedsearch/pull/391): Bump @babel/core from 7.13.13 to 7.13.14. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#390](https://github.com/PrestaShop/ps_facetedsearch/pull/390): Bump @babel/cli from 7.13.10 to 7.13.14. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#389](https://github.com/PrestaShop/ps_facetedsearch/pull/389): Bump @babel/register from 7.13.8 to 7.13.14. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#388](https://github.com/PrestaShop/ps_facetedsearch/pull/388): Bump @babel/node from 7.13.12 to 7.13.13. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#387](https://github.com/PrestaShop/ps_facetedsearch/pull/387): Bump @babel/core from 7.13.10 to 7.13.13. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### User documentation landing page
* [#43](https://github.com/PrestaShop/user-documentation-landing/pull/43): fix(deps): bump nuxt from 2.15.3 to 2.15.4. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#42](https://github.com/PrestaShop/user-documentation-landing/pull/42): fix(deps): bump core-js from 3.9.1 to 3.10.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#41](https://github.com/PrestaShop/user-documentation-landing/pull/41): chore(deps-dev): bump eslint from 7.22.0 to 7.23.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Wishlist block module
* [#107](https://github.com/PrestaShop/blockwishlist/pull/107): Bump y18n from 3.2.1 to 3.2.2. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Example modules
* [#48](https://github.com/PrestaShop/example-modules/pull/48): Bump y18n from 3.2.1 to 3.2.2 in /example_module_mailtheme. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#47](https://github.com/PrestaShop/example-modules/pull/47): Bump y18n from 3.2.1 to 3.2.2 in /demodoctrine/js. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### OnBoarding module
* [#103](https://github.com/PrestaShop/welcome/pull/103): Bump y18n from 4.0.0 to 4.0.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Stylelint configuration
* [#5](https://github.com/PrestaShop/stylelint-config/pull/5): Bump y18n from 4.0.0 to 4.0.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Docker images
* [#263](https://github.com/PrestaShop/docker/pull/263): Buid if the image not exists on Docker Hub platform, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#262](https://github.com/PrestaShop/docker/pull/262): Add quiet mode for the CI, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#261](https://github.com/PrestaShop/docker/pull/261): Add CI to automatically push Docker images, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#260](https://github.com/PrestaShop/docker/pull/260): Add versions for 1.7.7.3, by [@eternoendless](https://github.com/eternoendless)


### Stylelint browser compatibility plugin
* [#5](https://github.com/PrestaShop/stylelint-browser-compatibility/pull/5): Bump y18n from 4.0.0 to 4.0.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### PrestaShop contributors website
* [#52](https://github.com/PrestaShop/TopContributors/pull/52): Bump y18n from 4.0.0 to 4.0.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Auto Upgrade module
* [#392](https://github.com/PrestaShop/autoupgrade/pull/392): Improve link  to requirements. Thank you [@okom3pom](https://github.com/okom3pom)
* [#347](https://github.com/PrestaShop/autoupgrade/pull/347): Rename function name to avoid conflicts while upgrading several modules in a row, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### Core Weekly Generator tool
* [#79](https://github.com/PrestaShop/core-weekly-generator/pull/79): Bump y18n from 3.2.1 to 3.2.2. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Changes in developer documentation
* [#912](https://github.com/PrestaShop/docs/pull/912): Update optimizations.md. Thank you [@WebHelpersPau](https://github.com/WebHelpersPau)
* [#910](https://github.com/PrestaShop/docs/pull/910): Bump y18n from 4.0.0 to 4.0.1 in /src/themes/hugo-theme-learn/_src. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#909](https://github.com/PrestaShop/docs/pull/909): Add `table_label` option in `MaterialMultipleChoiceTableType`. Thank you [@PululuK](https://github.com/PululuK)


### Prestashop UI Kit
* [#147](https://github.com/PrestaShop/prestashop-ui-kit/pull/147): Fix long alerts breaks and wrong text split when multiple alerts, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#146](https://github.com/PrestaShop/prestashop-ui-kit/pull/146): Bump y18n from 3.2.1 to 3.2.2. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#145](https://github.com/PrestaShop/prestashop-ui-kit/pull/145): Mute traces of jQuery migrate if the UIKit is not in dev mode, by [@NeOMakinG](https://github.com/NeOMakinG)


### Email subscription module
* [#77](https://github.com/PrestaShop/ps_emailsubscription/pull/77): Release v2.6.1, by [@atomiix](https://github.com/atomiix)
* [#76](https://github.com/PrestaShop/ps_emailsubscription/pull/76): Bump version to 2.6.1, by [@atomiix](https://github.com/atomiix)


### Buy button lite module
* [#47](https://github.com/PrestaShop/ps_buybuttonlite/pull/47): Bump y18n from 3.2.1 to 3.2.2 in /app. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Issues Bot
* [#15](https://github.com/PrestaShop/issuebot/pull/15): Bump y18n from 4.0.0 to 4.0.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### PrestaShop PHPStan extension
* [#25](https://github.com/PrestaShop/phpstan-prestashop/pull/25): Add acceptance test for trait issue, by [@matks](https://github.com/matks)


### Quality Assurance module
* [#15](https://github.com/PrestaShop/ps_qualityassurance/pull/15): Migrated from Travis CI to Github Actions, by [@Progi1984](https://github.com/Progi1984)


### PrestaShop Specifications
* [#213](https://github.com/PrestaShop/prestashop-specs/pull/213): Multistore - Add spec for shops without URL, by [@marionf](https://github.com/marionf)
* [#210](https://github.com/PrestaShop/prestashop-specs/pull/210): Add specs and uat for listing in multistore, by [@marionf](https://github.com/marionf)
* [#179](https://github.com/PrestaShop/prestashop-specs/pull/179): Add image formats specifications & add multistore behaviors for image settings page, by [@LouiseBonnard](https://github.com/LouiseBonnard)


### User documentation (French)
* [#3](https://github.com/PrestaShop/user-documentation-fr/pull/3): Delete duplicate directory, by [@Julievrz](https://github.com/Julievrz)


### Share Buttons module
* [#49](https://github.com/PrestaShop/ps_sharebuttons/pull/49): Release v2.1.1. Thank you [@kpodemski](https://github.com/kpodemski)


### Email Alerts module
* [#84](https://github.com/PrestaShop/ps_emailalerts/pull/84): Release 2.3.0, by [@matks](https://github.com/matks)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@dependabot[bot]](https://github.com/apps/dependabot), [@Progi1984](https://github.com/Progi1984), [@jolelievre](https://github.com/jolelievre), [@boubkerbribri](https://github.com/boubkerbribri), [@PierreRambaud](https://github.com/PierreRambaud), [@NeOMakinG](https://github.com/NeOMakinG), [@matthieu-rolland](https://github.com/matthieu-rolland), [@okom3pom](https://github.com/okom3pom), [@rickygzz](https://github.com/rickygzz), [@WebHelpersPau](https://github.com/WebHelpersPau), [@eternoendless](https://github.com/eternoendless), [@atomiix](https://github.com/atomiix), [@matks](https://github.com/matks), [@PululuK](https://github.com/PululuK), [@github-actions[bot]](https://github.com/apps/github-actions), [@marionf](https://github.com/marionf), [@Julievrz](https://github.com/Julievrz), [@kpodemski](https://github.com/kpodemski), [@RomainBocheux](https://github.com/RomainBocheux), [@zuk3975](https://github.com/zuk3975), [@e-gaulue](https://github.com/e-gaulue), [@mkdgs](https://github.com/mkdgs), [@KminekMatej](https://github.com/KminekMatej), [@davidglezz](https://github.com/davidglezz), [@LouiseBonnard](https://github.com/LouiseBonnard), [@JevgenijVisockij](https://github.com/JevgenijVisockij), [@jbenezech](https://github.com/jbenezech), [@ks129](https://github.com/ks129), [@Quetzacoalt91](https://github.com/Quetzacoalt91)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

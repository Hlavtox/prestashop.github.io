---
layout: post
aliases: ["/news/coreweekly-32-2021"]
title:  "PrestaShop Core Weekly - Week 32 of 2021"
subtitle: "An inside look at the PrestaShop codebase"
date:   2021-08-17 09:00:00
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
twitter_image: /assets/images/theme/banner-core-weekly.jpg
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 9th to Sunday 15th of August 2021.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)



## A quick update about PrestaShop's GitHub issues and pull requests:

- [49 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2021-08-09..2021-08-15) have been created in the project repositories;
- [36 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2021-08-09..2021-08-15), including [1 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2021-08-09..2021-08-15) on the core;
- [82 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2021-08-09..2021-08-15) in the project repositories;
- [90 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2021-08-09..2021-08-15), including [64 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2021-08-09..2021-08-15).



## Code changes in the 'develop' branch


### Core
* [#25520](https://github.com/PrestaShop/PrestaShop/pull/25520): Fixed the use of deprecated functions in Uploader.php. Thank you [@WebHelpersPau](https://github.com/WebHelpersPau)


### Front office
* [#25543](https://github.com/PrestaShop/PrestaShop/pull/25543): Add `supplier` and `manufacturer` image link in `smarty url helper`. Thank you [@PululuK](https://github.com/PululuK)

## Changes in developer documentation

### Changes in developer documentation sources
* [#1123](https://github.com/PrestaShop/docs/pull/1123): fix: broken image link. Thank you [@maxime-aknin](https://github.com/maxime-aknin)
* [#1122](https://github.com/PrestaShop/docs/pull/1122): Remove weight from component pages so that they are sorted alphabetically, by [@eternoendless](https://github.com/eternoendless)
* [#1121](https://github.com/PrestaShop/docs/pull/1121): Remove weight from component pages so that they are sorted alphabetically, by [@eternoendless](https://github.com/eternoendless)
* [#1120](https://github.com/PrestaShop/docs/pull/1120): Update node version compatibility on 8.x documentation, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#1117](https://github.com/PrestaShop/docs/pull/1117): Update file structure for PS 8, by [@eternoendless](https://github.com/eternoendless)
* [#1116](https://github.com/PrestaShop/docs/pull/1116): Update architecture introduction for PS 8, by [@eternoendless](https://github.com/eternoendless)
* [#1114](https://github.com/PrestaShop/docs/pull/1114): Make PS 8 articles link to the same version + remove invalid aliases, by [@eternoendless](https://github.com/eternoendless)
* [#1113](https://github.com/PrestaShop/docs/pull/1113): Update development environment doc for 8.0, by [@eternoendless](https://github.com/eternoendless)
* [#1112](https://github.com/PrestaShop/docs/pull/1112): Update system requirements for PS 8, by [@eternoendless](https://github.com/eternoendless)
* [#1111](https://github.com/PrestaShop/docs/pull/1111): Fix number of native modules, by [@eternoendless](https://github.com/eternoendless)
* [#1110](https://github.com/PrestaShop/docs/pull/1110): Update branch setting for build, by [@matks](https://github.com/matks)
* [#1109](https://github.com/PrestaShop/docs/pull/1109): Update index for 8.x, by [@matks](https://github.com/matks)
* [#1077](https://github.com/PrestaShop/docs/pull/1077): Fixed hook locations of twig files, by [@Progi1984](https://github.com/Progi1984)


### Changes in developer documentation theme
* [#4](https://github.com/PrestaShop/ps-docs-theme/pull/4): Fix layout when using description in children list, by [@eternoendless](https://github.com/eternoendless)
* [#3](https://github.com/PrestaShop/ps-docs-theme/pull/3): Add missing static 404 image, by [@matks](https://github.com/matks)
* [#2](https://github.com/PrestaShop/ps-docs-theme/pull/2): Brand the devdocs 404 page in PrestaShop spirit, by [@matks](https://github.com/matks)


### Changes in developer documentation site
* [#5](https://github.com/PrestaShop/devdocs-site/pull/5): Fetch 0 depth for submodule to allow git pull --recurse-submodules to success, by [@matks](https://github.com/matks)
* [#2](https://github.com/PrestaShop/devdocs-site/pull/2): Add 8.x docs branch as submodule, by [@matks](https://github.com/matks)


## Code changes in modules, themes & tools


### Example modules
* [#77](https://github.com/PrestaShop/example-modules/pull/77): Bump url-parse from 1.5.1 to 1.5.3 in /example_module_mailtheme. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#76](https://github.com/PrestaShop/example-modules/pull/76): Bump path-parse from 1.0.6 to 1.0.7 in /demodoctrine/js. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#75](https://github.com/PrestaShop/example-modules/pull/75): Bump tar from 4.4.8 to 4.4.15 in /example_module_mailtheme. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### PrestaShop Specifications
* [#239](https://github.com/PrestaShop/prestashop-specs/pull/239): Fixed logo display, by [@Progi1984](https://github.com/Progi1984)
* [#238](https://github.com/PrestaShop/prestashop-specs/pull/238): Bump version Hugo to 0.85.0, by [@Progi1984](https://github.com/Progi1984)
* [#237](https://github.com/PrestaShop/prestashop-specs/pull/237): Migrated from hugo-geekdoc to ps-docs-theme, by [@Progi1984](https://github.com/Progi1984)


### OnBoarding module
* [#124](https://github.com/PrestaShop/welcome/pull/124): Bump path-parse from 1.0.6 to 1.0.7. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#121](https://github.com/PrestaShop/welcome/pull/121): Bump eslint-plugin-import from 2.23.4 to 2.24.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Faceted search module
* [#491](https://github.com/PrestaShop/ps_facetedsearch/pull/491): Bump @babel/register from 7.14.5 to 7.15.3. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#490](https://github.com/PrestaShop/ps_facetedsearch/pull/490): Bump webpack from 5.49.0 to 5.50.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#489](https://github.com/PrestaShop/ps_facetedsearch/pull/489): Bump path-parse from 1.0.6 to 1.0.7. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#488](https://github.com/PrestaShop/ps_facetedsearch/pull/488): Bump webpack from 5.47.0 to 5.49.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#487](https://github.com/PrestaShop/ps_facetedsearch/pull/487): Bump eslint-plugin-import from 2.23.4 to 2.24.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#486](https://github.com/PrestaShop/ps_facetedsearch/pull/486): Bump @babel/preset-env from 7.14.8 to 7.15.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#485](https://github.com/PrestaShop/ps_facetedsearch/pull/485): Bump @babel/core from 7.14.8 to 7.15.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#484](https://github.com/PrestaShop/ps_facetedsearch/pull/484): Bump tar from 6.1.0 to 6.1.3. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#482](https://github.com/PrestaShop/ps_facetedsearch/pull/482): Bump @babel/node from 7.14.7 to 7.14.9. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### User documentation landing page
* [#106](https://github.com/PrestaShop/user-documentation-landing/pull/106): fix(deps): bump nuxt from 2.15.7 to 2.15.8. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#105](https://github.com/PrestaShop/user-documentation-landing/pull/105): fix(deps): bump core-js from 3.15.2 to 3.16.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#104](https://github.com/PrestaShop/user-documentation-landing/pull/104): fix(deps): bump actions/setup-node from 2.3.0 to 2.4.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#103](https://github.com/PrestaShop/user-documentation-landing/pull/103): chore(deps-dev): bump sass from 1.35.2 to 1.37.5. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#98](https://github.com/PrestaShop/user-documentation-landing/pull/98): chore(deps-dev): bump eslint from 7.31.0 to 7.32.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Stylelint browser compatibility plugin
* [#12](https://github.com/PrestaShop/stylelint-browser-compatibility/pull/12): Bump path-parse from 1.0.6 to 1.0.7. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Stylelint configuration
* [#20](https://github.com/PrestaShop/stylelint-config/pull/20): Bump path-parse from 1.0.6 to 1.0.7. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Core Weekly Generator tool
* [#100](https://github.com/PrestaShop/core-weekly-generator/pull/100): Bump path-parse from 1.0.6 to 1.0.7. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#99](https://github.com/PrestaShop/core-weekly-generator/pull/99): Bump color-string from 1.5.3 to 1.6.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#98](https://github.com/PrestaShop/core-weekly-generator/pull/98): Bump tar from 4.4.8 to 4.4.15. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#97](https://github.com/PrestaShop/core-weekly-generator/pull/97): Raise an exception if one fetched PR branch is unknown, by [@matks](https://github.com/matks)


### Buy button lite module
* [#54](https://github.com/PrestaShop/ps_buybuttonlite/pull/54): Bump url-parse from 1.5.1 to 1.5.3 in /app. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#52](https://github.com/PrestaShop/ps_buybuttonlite/pull/52): Bump path-parse from 1.0.5 to 1.0.7 in /app. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Customer reassurance block module
* [#253](https://github.com/PrestaShop/blockreassurance/pull/253): Bump webpack from 5.49.0 to 5.50.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#252](https://github.com/PrestaShop/blockreassurance/pull/252): Bump tar from 6.1.0 to 6.1.6. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#251](https://github.com/PrestaShop/blockreassurance/pull/251): Bump webpack from 5.47.0 to 5.49.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#250](https://github.com/PrestaShop/blockreassurance/pull/250): Bump eslint-plugin-import from 2.23.4 to 2.24.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#249](https://github.com/PrestaShop/blockreassurance/pull/249): Bump @babel/core from 7.14.8 to 7.15.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#248](https://github.com/PrestaShop/blockreassurance/pull/248): Bump mini-css-extract-plugin from 2.1.0 to 2.2.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Wishlist block module
* [#127](https://github.com/PrestaShop/blockwishlist/pull/127): Fix CI build by building only compiled files, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#126](https://github.com/PrestaShop/blockwishlist/pull/126): Bump tar from 4.4.13 to 4.4.15. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Docker images
* [#271](https://github.com/PrestaShop/docker/pull/271): Release 1.7.7.6, by [@matthieu-rolland](https://github.com/matthieu-rolland)


### Quality Assurance module
* [#19](https://github.com/PrestaShop/ps_qualityassurance/pull/19): Improve default payload to use var_export, by [@matks](https://github.com/matks)


### Prestashop UI Kit
* [#168](https://github.com/PrestaShop/prestashop-ui-kit/pull/168): Bump tar from 6.1.0 to 6.1.3. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### TranslationTools Bundle
* [#98](https://github.com/PrestaShop/TranslationToolsBundle/pull/98): Add a Symfony integration test, by [@matks](https://github.com/matks)
* [#96](https://github.com/PrestaShop/TranslationToolsBundle/pull/96): Remove Scrutinizer, add badges for GitHub Actions and Coverall, by [@matks](https://github.com/matks)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@dependabot[bot]](https://github.com/apps/dependabot), [@Progi1984](https://github.com/Progi1984), [@maxime-aknin](https://github.com/maxime-aknin), [@eternoendless](https://github.com/eternoendless), [@NeOMakinG](https://github.com/NeOMakinG), [@matks](https://github.com/matks), [@matthieu-rolland](https://github.com/matthieu-rolland), [@PululuK](https://github.com/PululuK), [@WebHelpersPau](https://github.com/WebHelpersPau)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

---
layout: post
aliases: ["/news/coreweekly-07-2021"]
title:  "PrestaShop Core Weekly - Week 7 of 2021"
subtitle: "An inside look at the PrestaShop codebase"
date:   2021-02-23
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
twitter_image: /assets/images/theme/banner-core-weekly.jpg
icon: icon-calendar
tags:
 - core-monthly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 15th to Sunday 21th of February 2021.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)

## General messages

Dear developers,

Last week the maintainers team focused on [delivering PrestaShop 1.7.7.2](https://build.prestashop.com/news/prestashop-1-7-7-2-maintenance-release/) which was achieved on time, on this Monday 22nd of February 2021! We are very happy of this outcome.

Did you also notice our [Public Online Demonstrations](https://build.prestashop.com/news/first-public-oss-demo/) announcement? If you want to attend the next one, it will be at 2pm CET on Thursday, 25th of February, streamed live on our newly created [YouTube channel](https://www.youtube.com/channel/UCchgBHHhl5Vu7HgjrzpvVQQ)!

Follow [this link](https://youtu.be/JBvJgoo-rLg) to attend the second session.


## Releases

* [PrestaShop](https://github.com/PrestaShop/PrestaShop) [1.7.7.2](https://github.com/PrestaShop/PrestaShop/releases/tag/1.7.7.2)
* [ps_categorytree](https://github.com/PrestaShop/ps_categorytree) module: [v2.0.2](https://github.com/PrestaShop/ps_categorytree/releases/tag/v2.0.2)


## A quick update about PrestaShop's GitHub issues and pull requests:

- [40 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2021-02-15..2021-02-21) have been created in the project repositories;
- [43 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2021-02-15..2021-02-21), including [4 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2021-02-15..2021-02-21) on the core;
- [47 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2021-02-15..2021-02-21) in the project repositories;
- [42 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2021-02-15..2021-02-21), including [37 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2021-02-15..2021-02-21).



## Code changes in the 'develop' branch


### Core
* [#23272](https://github.com/PrestaShop/PrestaShop/pull/23272): Fix $to and $toName type in docblock. Thank you [@RomainMazB](https://github.com/RomainMazB)


### Back office
* [#23283](https://github.com/PrestaShop/PrestaShop/pull/23283): Fix textbox not clickable of tinymce because of z-index, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#23159](https://github.com/PrestaShop/PrestaShop/pull/23159): Integrate Product features form, by [@jolelievre](https://github.com/jolelievre)
* [#23155](https://github.com/PrestaShop/PrestaShop/pull/23155): Adjust notifications and profile modal on mobile on default theme, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#23128](https://github.com/PrestaShop/PrestaShop/pull/23128): Integrate customizationFields in product form options tab. Thank you [@zuk3975](https://github.com/zuk3975)


### Tests
* [#23297](https://github.com/PrestaShop/PrestaShop/pull/23297): Fix Nightly 18-02-2021 . Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#23264](https://github.com/PrestaShop/PrestaShop/pull/23264): Fix CI problems related to new ps_linklist version, by [@jolelievre](https://github.com/jolelievre)


## Code changes in the '1.7.7.x' branch


### Core
* [#23276](https://github.com/PrestaShop/PrestaShop/pull/23276): Update composer version of ps_categorytree, by [@atomiix](https://github.com/atomiix)


### Back office
* [#23289](https://github.com/PrestaShop/PrestaShop/pull/23289): Use default currency when supplier currency setting is incorrect, by [@atomiix](https://github.com/atomiix)


## Code changes in modules, themes & tools


### Changes in developer documentation
* [#868](https://github.com/PrestaShop/docs/pull/868): Changed the link to the example module for the mail theme, by [@Progi1984](https://github.com/Progi1984)
* [#863](https://github.com/PrestaShop/docs/pull/863): Add documentation of hookActionValidateStepComplete. Thank you [@Hlavtox](https://github.com/Hlavtox)
* [#861](https://github.com/PrestaShop/docs/pull/861): Add a security section. Thank you [@jf-viguier](https://github.com/jf-viguier)
* [#859](https://github.com/PrestaShop/docs/pull/859): Fix error in executeS return description and add a notice. Thank you [@jf-viguier](https://github.com/jf-viguier)
* [#858](https://github.com/PrestaShop/docs/pull/858): Add DB::delete method. Thank you [@jf-viguier](https://github.com/jf-viguier)
* [#857](https://github.com/PrestaShop/docs/pull/857): Update update method description. Thank you [@jf-viguier](https://github.com/jf-viguier)


### Example modules
* [#44](https://github.com/PrestaShop/example-modules/pull/44): Added Module mailtheme, by [@Progi1984](https://github.com/Progi1984)


### Faceted search module
* [#339](https://github.com/PrestaShop/ps_facetedsearch/pull/339): Bump @babel/node from 7.12.16 to 7.12.17. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#338](https://github.com/PrestaShop/ps_facetedsearch/pull/338): Bump @babel/core from 7.12.16 to 7.12.17. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#337](https://github.com/PrestaShop/ps_facetedsearch/pull/337): Bump webpack from 5.22.0 to 5.23.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#336](https://github.com/PrestaShop/ps_facetedsearch/pull/336): Bump @babel/cli from 7.12.16 to 7.12.17. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#335](https://github.com/PrestaShop/ps_facetedsearch/pull/335): Bump @babel/preset-env from 7.12.16 to 7.12.17. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#334](https://github.com/PrestaShop/ps_facetedsearch/pull/334): Bump webpack from 5.21.2 to 5.22.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Customer reassurance block module
* [#133](https://github.com/PrestaShop/blockreassurance/pull/133): Bump mini-css-extract-plugin from 1.3.7 to 1.3.8. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#132](https://github.com/PrestaShop/blockreassurance/pull/132): Bump @babel/core from 7.12.16 to 7.12.17. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#131](https://github.com/PrestaShop/blockreassurance/pull/131): Bump webpack from 5.22.0 to 5.23.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#130](https://github.com/PrestaShop/blockreassurance/pull/130): Bump webpack from 5.21.2 to 5.22.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#129](https://github.com/PrestaShop/blockreassurance/pull/129): Bump mini-css-extract-plugin from 1.3.6 to 1.3.7. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### User documentation landing page
* [#29](https://github.com/PrestaShop/user-documentation-landing/pull/29): chore(deps-dev): bump sass from 1.32.7 to 1.32.8. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#28](https://github.com/PrestaShop/user-documentation-landing/pull/28): fix(deps): bump core-js from 3.8.3 to 3.9.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#27](https://github.com/PrestaShop/user-documentation-landing/pull/27): fix(deps): bump nuxt from 2.14.12 to 2.15.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#26](https://github.com/PrestaShop/user-documentation-landing/pull/26): chore(deps-dev): bump eslint from 7.19.0 to 7.20.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Wishlist block module
* [#99](https://github.com/PrestaShop/blockwishlist/pull/99): Fix 'is same' smarty function for stats template. Thank you [@pablopolyte](https://github.com/pablopolyte)


### Category tree links module
* [#50](https://github.com/PrestaShop/ps_categorytree/pull/50): Release v2.0.2, by [@atomiix](https://github.com/atomiix)
* [#49](https://github.com/PrestaShop/ps_categorytree/pull/49): Bump version to 2.0.2, by [@atomiix](https://github.com/atomiix)
* [#26](https://github.com/PrestaShop/ps_categorytree/pull/26): Uninstall module used on PS 1.6 before using this one, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### PrestaShop PHPStan extension
* [#7](https://github.com/PrestaShop/phpstan-prestashop/pull/7): Add MIT license headers, by [@matks](https://github.com/matks)


### Share Buttons module
* [#28](https://github.com/PrestaShop/ps_sharebuttons/pull/28): Uninstall module used on PS 1.6 before using this one, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


## Where to start contributing?

What about updating the Order Confirmation email template [to remove the gift line when gift option is disabled](https://github.com/PrestaShop/PrestaShop/issues/22825)? This is a bug report submitted one month ago, and it is one of our [good first issues](https://github.com/PrestaShop/PrestaShop/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22).

Good first issues are a list of all beginner-friendly improvements and bugs to fix in the project. You can read more about this label on [our article about it](https://build.prestashop.com/news/a-definition-of-the-good-first-issue-label).

<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@Progi1984](https://github.com/Progi1984), [@dependabot[bot]](https://github.com/apps/dependabot), [@nesrineabdmouleh](https://github.com/nesrineabdmouleh), [@pablopolyte](https://github.com/pablopolyte), [@atomiix](https://github.com/atomiix), [@NeOMakinG](https://github.com/NeOMakinG), [@RomainMazB](https://github.com/RomainMazB), [@jolelievre](https://github.com/jolelievre), [@matks](https://github.com/matks), [@Hlavtox](https://github.com/Hlavtox), [@jf-viguier](https://github.com/jf-viguier), [@zuk3975](https://github.com/zuk3975), [@Quetzacoalt91](https://github.com/Quetzacoalt91)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

---
layout: post
aliases: ["/news/coreweekly-53-2020"]
slug: "coreweekly-53-2020"
title:  "PrestaShop Core Weekly - Last week of 2020"
subtitle: "An inside look at the PrestaShop codebase"
date:   2021-01-06
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
twitter_image: /assets/images/theme/banner-core-weekly.jpg
icon: icon-calendar
tags:
 - core-weekly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 28th of December 2020 to Sunday 3rd of January 2021.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)

## General messages

Happy new year to you, dear contributors and community members! Contributors and maintainers slowly come back from time off and activity increases back on the GitHub repositories.

During December holidays, QA team tested the 1.7.7.1 candidate release and reported some issues of this build. Only one is significant enough to prevent the release from happening: [an issue preventing upgrade from PrestaShop 1.6 to PrestaShop 1.7.7](https://github.com/PrestaShop/PrestaShop/issues/22668). The scope of the release has been updated accordingly.

Once this bug is fixed, the road should be open for [1.7.7.1 public release](https://github.com/PrestaShop/PrestaShop/issues/22306#issuecomment-754737943)!

Another notice: following increased performance issues on our current CI pipeline, we are slowly migrating our CI to [GitHub Actions](https://github.com/features/actions). We had previously explored GitHub Actions capacities on modules to validate it as a suitable solution and we are now moving into the next phase.


## A quick update about PrestaShop's GitHub issues and pull requests:

- [39 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2020-12-28..2021-01-03) have been created in the project repositories;
- [29 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2020-12-28..2021-01-03), including [1 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2020-12-28..2021-01-03) on the core;
- [27 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2020-12-28..2021-01-03) in the project repositories;
- [12 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2020-12-28..2021-01-03), including [10 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2020-12-28..2021-01-03).
        


## Code changes in the 'develop' branch


### Back office
* [#22614](https://github.com/PrestaShop/PrestaShop/pull/22614): Move SpecificPrice command and handlers into a product sub domain, by [@jolelievre](https://github.com/jolelievre)


### Tests
* [#22567](https://github.com/PrestaShop/PrestaShop/pull/22567): Migrated Unit Tests & Linter from Travis CI to Github Actions, by [@Progi1984](https://github.com/Progi1984)


## Code changes in modules, themes & tools


### Customer reassurance block module
* [#101](https://github.com/PrestaShop/blockreassurance/pull/101): Bump webpack from 5.11.0 to 5.11.1. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#100](https://github.com/PrestaShop/blockreassurance/pull/100): Bump webpack-cli from 4.2.0 to 4.3.0. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#99](https://github.com/PrestaShop/blockreassurance/pull/99): Bump friendsofphp/php-cs-fixer from 2.17.2 to 2.17.3. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### Faceted search module
* [#298](https://github.com/PrestaShop/ps_facetedsearch/pull/298): Bump webpack from 5.10.3 to 5.11.1. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### PrestaShop Virtual Machine
* [#7](https://github.com/PrestaShop/vagrant/pull/7): Allow people to use MailCatcher as SMTP, by [@PierreRambaud](https://github.com/PierreRambaud)


### Customer "Sign in" link module
* [#30](https://github.com/PrestaShop/ps_customersignin/pull/30): Bump prestashop/php-dev-tools from 3.12 to 3.13. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### Nightly board
* [#50](https://github.com/PrestaShop/nightly-board/pull/50): Add PWA, correct lint, add noreferrer to link, by [@NeOMakinG](https://github.com/NeOMakinG)

## Where to start contributing?

What about adding [fixing some minor display issues in autoupgrade module](https://github.com/PrestaShop/PrestaShop/issues/20097)? This is a bug reported some months ago, and it is one of our [good first issues](https://github.com/PrestaShop/PrestaShop/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22).

Good first issues are a list of all beginner-friendly improvements and bugs to fix in the project. You can read more about this label on [our article about it](https://build.prestashop.com/news/a-definition-of-the-good-first-issue-label).

<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@jolelievre](https://github.com/jolelievre), [@dependabot[bot]](https://github.com/apps/dependabot), [@PierreRambaud](https://github.com/PierreRambaud), [@NeOMakinG](https://github.com/NeOMakinG), [@Progi1984](https://github.com/Progi1984)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!


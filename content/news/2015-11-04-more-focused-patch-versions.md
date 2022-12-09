---
layout: post
title:  "Our plan for more regular & focused patch versions"
subtitle: "Fixing more issues in due time!"
date:   2015-11-04 14:00:00
authors: [jeromenadaud, xavierborderie]
icon: icon-random
tags:
 - patch
 - version
 - development
 - 1.6
---

With the adoption of [SemVer](http://build.prestashop.com/news/a-more-semantic-versioning-scheme/)-like versioning, we know that a patch version will only feature non-breaking changes, making it far safer to update to PrestaShop than ever before... and thus safer for us to release patch version more regularly.

As a reminder, this is how [SemVer](http://semver.org/) works:

> Given a version number MAJOR.MINOR.PATCH, increment the:
>
> - MAJOR version when you make incompatible API changes,
> - MINOR version when you add functionality in a backwards-compatible manner, and
> - PATCH version when you make backwards-compatible bug fixes.
>
> Additional labels for pre-release and build metadata are available as extensions to the MAJOR.MINOR.PATCH format.

We plan on adopting a new release process in order to give merchants and developers more predictable releases, with a higher level of transparency.

### The goals

The goals of this new release process are thus:

* Shorten the release cycle -- have more patch versions, with a more focused scope (10-15 issues each), making them easier to apply.
* Give more visibility to the contributing developers, and show that they are an essential part of PrestaShop.
* Improve the experience for PrestaShop contributors, both on GitHub and on the Forge -- without forgetting Crowdin or the forum.
* Give time to the PrestaShop ecosystem to catch up with the upcoming major/minor versions.


### The release process

In short: more regular and more focused patch versions.

Ever since we chose to follow a [SemVer-like versioning](http://http://build.prestashop.com/news/a-more-semantic-versioning-scheme/), PrestaShop's developers have wanted to manage the releases through a time-based model -- meaning that we want to make regular releases rather than trying to find a balance between "let's fix all the things!" and "merchants need a bug fix release as soon as possible!"

Now that we are ensuring that patch releases (which are essentially backward-compatible bugfix versions) are well-tested and more focused, we think we can provide our users with a more regular schedule. 

This allows us to perfect the maintenance phase of PrestaShop 1.6 for the coming months. More on that very soon!


### So, does that mean more updates are coming?

Yes! 

All this means that we want to stop waiting to have 200 code changes before we release a patch version. We know that both merchants and developers need bug fixed NOW. 

Since patch versions are built to be safe upgrades for the current major or minor version, we think we owe it to you to release fixes more often -- probably every 2-3 weeks, with 10-15 issues each.

Note that this plan is only for patch versions (1.6.1.3, 1.6.1.4, etc.), NOT for minor versions (1.6.2.0, 1.6.3.0, etc.) nor for major versions (1.7.0.0, 1.8.0.0, etc.).

We are confident this system of safe patch versions will increase your trust in upgrading PrestaShop.

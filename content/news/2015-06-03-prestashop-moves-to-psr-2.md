---
layout: post
title:  "PrestaShop && the PSR-2 coding style guide"
subtitle: "Adopting a common coding standard"
date:   2015-06-03 18:54:00
authors:  [ jeromenadaud ]
icon: icon-code
tags: [coding-standards]
published: true
---

We are planning to switch to PSR-2, here is the why, the how and the when!

### The current situation

PrestaShop currently uses its own [Coding Standards](http://doc.prestashop.com/display/PS16/Coding+Standards), based on [PSR-1](http://www.php-fig.org/psr/psr-1/), with a few adaptations for historical reasons.

For a long time, we've wanted to move to a more generally-accepted coding standard. PrestaShop is loved by its community and we love our community, and we wanted to adopt a common coding standard in order to ease code contribution.

There are a few coding standards in use: [PHP's PEAR project has its own](https://pear.php.net/manual/en/standards.php), [the Zend Framework has one](http://framework.zend.com/manual/current/en/ref/coding.standard.html), [WordPress has one too](https://make.wordpress.org/core/handbook/coding-standards/php/), [Drupal derives its standard from the PEAR one](https://www.drupal.org/coding-standards), ...and then there is the [PSR-1 coding standard](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-1-basic-coding-standard.md), along with the [PSR-2 coding style guide](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md).

PSR-1 and PSR-2, named "Basic Coding Standard" and "Coding Style Guide", were conceived by the PHP Framework Interop Group, an informal group of representatives from major PHP projects, which offers a place to "talk about the commonalities between our projects and find ways we can work together" ([see the FAQ](http://www.php-fig.org/faq/)). The group issues a series of standards (PSRs, or PHP Standard Recommendation) on how to best build a PHP project.

We started a [poll about moving the PrestaShop codebase to PSR-2](https://www.prestashop.com/forums/topic/434831-psr2-development-norm-for-prestashop/) (and therefore PSR-1 too) back on April 1st, and the result was clearly positive: 84.62% of the respondents agreed that this was a good idea!

So, time to prepare for that move!


### When will it happen, and how?

#### 1. State of the current code

[PrestaShop's planned new architecture](http://build.prestashop.com/news/new-architecture-1-6-1-0/) already follows the PSR-2 coding style. For instance, check [the new Core_Business_Payment_PaymentOption.php class](https://github.com/PrestaShop/PrestaShop/blob/1.6/Core/Business/Payment/Core_Business_Payment_PaymentOption.php).

For the remaining PrestaShop core code (classes, controllers, etc.), we will start moving all files from the PrestaShop coding standards to PSR-2 once PrestaShop 1.6.1.0 has been released.

Please be bear with us, as there might bugs along the way: changing coding style is not automatic, and it will be a way for us to revise some old code and make the whole codebase stronger.

In any case, you can participate to this project just by making a pull request! Please have a look at [PrestaShop contribution process](https://github.com/PrestaShop/PrestaShop/blob/1.6/CONTRIBUTING.md) in order to help us move things faster and with more confidence! We will need code contributors, but also reviewers and testers!

#### 2. Start of the PSR-2 era

In effect, from the moment PrestaShop 1.6.1.0 is released, the **next pull requests will HAVE TO follow the PSR-1 and PSR-2 standards**. Update your tools and methods!

#### 3. About pull requests that are currently waiting for a code review

Many pull requests were written before we announced the project to move to PSR-2.

Don't worry, we will merge them as-is, and correct their use of PSR-2 afterwards ourselves.

Obviously, you are more than welcome to upgrade your PRs to PSR-2 yourself :)

#### 4. About existing PrestaShop modules

All existing modules' contributors have worked hard to follow the PrestaShop Coding Standards over the years.

The fact that PrestaShop is changing and is going to use a common coding standard doesn't mean existing modules will suddenly stop being valid!

The [PrestaShop validator](https://validator.prestashop.com) will not reject modules if they follow the old standard for quite some time.

For your future modules, please follow the PSR-2 coding standards: this will benefit the whole community.


### The main differences between the current norm and PSR-2

Now it is time to see where the PrestaShop Coding Standards and PSR-2 differ.

<div class="alert alert-important" role="alert">
<h4><i class='icon-fire'></i> Important</h4>
At the time of writing, namespaces and closures are not allowed, because we first need to announce the switch to PHP 5.4 as the minimum version supported by PrestaShop.

This will be announced very soon, and applied in the coming year.
</div>

#### 1. Lines

The soft limit on line length MUST be 120 characters; automated style checkers MUST warn but MUST NOT error at the soft limit.

#### 2. Keywords

The PHP constants true, false, and null MUST be in lower case.

#### 3. Properties

Property names SHOULD NOT be prefixed with a single underscore to indicate protected or private visibility.

#### 4. Methods

Method names SHOULD NOT be prefixed with a single underscore to indicate protected or private visibility.

#### 5. Conditions

##### 5.1. if, elseif, else

An `if` structure looks like the following. Note the placement of parenthesis, spaces, and braces; and that `else` and `elseif` are on the same line as the closing brace from the earlier body.

{% highlight php startinline=true %}
if ($expr1) {
    // if body
} elseif ($expr2) {
    // elseif body
} else {
    // else body;
}
{% endhighlight %}

##### 5.2. switch, case

A `switch` structure looks like the following. Note the placement of parenthesis, spaces, and braces. The case statement MUST be indented once from switch, and the break keyword (or other terminating keyword) MUST be indented at the same level as the case body. There MUST be a comment such as `// no break` when fall-through is intentional in a non-empty case body.

{% highlight php startinline=true %}
switch ($expr) {
    case 0:
        echo 'First case, with a break';
        break;
    case 1:
        echo 'Second case, which falls through';
        // no break
    case 2:
    case 3:
    case 4:
        echo 'Third case, return instead of break';
        return;
    default:
        echo 'Default case';
        break;
}
{% endhighlight %}

##### 5.3. while, do while, for, foreach, try, catch

A `while` statement looks like the following. Note the placement of parenthesis, spaces, and braces.

{% highlight php startinline=true %}
while ($expr) {
    // structure body
}
{% endhighlight %}

Similarly, a `do while` statement looks like the following. Note the placement of parenthesis, spaces, and braces.

{% highlight php startinline=true %}
do {
    // structure body;
} while ($expr);
{% endhighlight %}

A `for` statement looks like the following. Note the placement of parenthesis, spaces, and braces.

{% highlight php startinline=true %}
for ($i = 0; $i < 10; $i++) {
    // for body
}
{% endhighlight %}

A `foreach` statement looks like the following. Note the placement of parenthesis, spaces, and braces.

{% highlight php startinline=true %}
foreach ($iterable as $key => $value) {
    // foreach body
}
{% endhighlight %}

A try catch block looks like the following. Note the placement of parenthesis, spaces, and braces.

{% highlight php startinline=true %}
try {
    // try body
} catch (FirstExceptionType $e) {
    // catch body
} catch (OtherExceptionType $e) {
    // catch body
}
{% endhighlight %}

### End of an era, beginning of a new one!

The switch to PSR-2 is just another mark of the changes that are happening at PrestaShop. More exciting things are coming, stay tuned!

If you have any question about this switch, let us know in the comments!

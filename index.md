---
layout: home
title: About
tab: about
---

# The Toadsuck Project for PHP

What is the Toadsuck Project?

It is a "glue" project created by [Josh Moody](http://www.joshmoody.com). It is designed to assist with bringing
together the components you need to build an application without all the overhead and learning curve associated
with the big PHP frameworks.

The Toadsuck Project is *NOT* a framework.
 
I appreciate the hard work that has gone into creating these amazing PHP frameworks. I just think full stack frameworks
are overkill for many developers working on small-ish projects.

Here's what I really need when writing applications:

- Routing
- Templating
- Database Abstraction
- Per-Environment Configuration (local, test, stage, prod)
- Unit Tests

The goal of the Toadsuck project is to bring together into a cohesive package some of the best components in the community that meet these needs.
There are over 20,000 libraries available on [Packagist](https://packagist.org/). Surely there is one there to fit just about every need.

This is also an experiment to see if you really can build a system composed entirely of other components
without actually using a framework (or building a framework in the process).

At present, the Toadsuck project consists of 2 components:

- [Toadsuck.Core](https://github.com/toadsuck/toadsuck-core) : A front controller that provides routing and dispatching powered by
[Aura.Router](https://github.com/auraphp/Aura.Router) from [The Aura Project for PHP](http://auraphp.com/)

- [Toadsuck.Skeleton](https://github.com/toadsuck/toadsuck-skeleton): A simple web application skeleton implementing
the front controller from Toadsuck.Core.

Check back soon to see how the project is progressing.


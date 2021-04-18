---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

## NO-LOCKS manifesto

When it comes to building multi-threaded programs, as a general approach, we believe the following:
1. using locks is an anti-pattern -- they should be replaced by higher level abstractions
1. using raw threads is an anti-pattern -- they should be replaced by higher level abstractions
1. concurrency should be approached from the design phase, similar to designing functional aspects
1. concurrency should be approached top-down
1. concurrency abstractions should be able to be decomposed
1. concurrency abstractions should be easily decomposable/composable

## Some alternatives
* tasks
* immutability
* actor-based programming
* communicating sequential processes (or other forms of message passing)
* reactive programming

---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

## NO-locks manifesto

When it comes to building multi-threaded programs, as a general approach, we believe the following:
1. using locks is bad -- they should be replaced by higher level abstractions
1. using raw threads is bad -- they should be replaced by higher level abstractions
1. concurrency should be approached from the design phase
1. concurrency should be approached top-down
1. concurrency abstractions should be able to be decomposed
1. concurrency abstractions should be easily composable
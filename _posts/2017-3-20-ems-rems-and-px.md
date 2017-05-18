---
layout: post
title: The Differences between EM, REM and PX
---

One of my first confusions, when I looked at the company's code, was the difference usages of units of measure used in the `SCSS`. There is `px`, `em`, and `rem`, I noticed that `rem` is used primarily for the margin and padding, but `px` is used for the sizing of images or icons. I didn't understand the reasoning behind this until I started to do my research.



## rem and em are not the same

`rem` and `em` are both flexible and scalable to make designs easier to adjust. The pixel value of `rem` units are dependent on the root font size of the site, i.e. the HTML element. the root font size is multiplied by the number you're using for `rem`.

The pixel value of `em` units are dependent on the font size of the element being styled, the element's font size is multiplied by the number you’re using for `em`. The one issue that `em` suffers from is the effects of inheritance, which can only be overridden by setting font size in units that are not subject to the inheritance, like `px` or `vw`.

`rem` appears to be the preferred unit of choice because whatever font size the user has their browser set to, the layout will adjust and provide consistent sizing regardless of inheritance.



## Pixels should still be used

We're all accustomed to using `px` for sizing, the problem with that is if you set a heading at `30px`, it will always remain `30px`, no matter the user's font size settings. Everyone can agree that designing your page so that it is accommodating to everyone is good. One way of doing that is allowing users to make the text of your site bigger and easier to read. If you specify the font size in `px`, the font wouldn’t scale when the user changes the browser’s font size option. There are still uses for `px`, and it shouldn’t entirely be dismissed in your code. You should use both pixels and rem. So newer browsers get `rem` and old browsers fall back to pixels. This can be automated with Sass or Less so all you do is enter the `px` value and it automatically outputs `px` and `rem`.



## Using em for media queries

We use `em` for media queries because it remains the most consistent in resizing breakpoints through different browsers. Here's a very informative blog post about why using `em` is preferred for media queries: Media query units



## TL; DR

* Pixels are used for fall back for older browsers.

* Use REMs for sizes and spacing.

* Use EMs for media queries.

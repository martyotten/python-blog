# Minimalist Responsive Personal Landing Page

My minimalist **responsive** personal landing page with cover background image and social media links.

#### It works on all devices in landscape and portrait orientations.
It uses _fluid sizing_ and _spacing_, _tailored background image selection_ through media queries, and enhanced _accessibility_ through _ARIA attributes_ and _keyboard_ accessibility.

* Background image can be changed with the button in the bottom right corner
* Optimal page load speeds with minimal HTTP requests (reduced latency), reduced file sizes, and targeted preloading.
* Alternate background images are preload depending on device screen size and orientation
* When hovering over or focused on a main icon, see through to the background image with inline SVGs
* Everything is keyboard accessible



### Check it out **[here](http://jorypestorious.com)**

---

#### Issues
* **IE 11** - CSS fill transition does not work for SVG elements
 * So I removed the transition on the SVG fill, but it feels a bit more harsh
* **IE 10** and below does not support CSS transforms on SVG elements (though SVG transform attributes do work)
 * So the subtle scaling-in on hover and focus might not work on older versions of IE
* ~~**Change Background button** does not have keyboard accessibility~~
 * Fixed
* ~~**Change Background button** is not working on the default Android browser~~
  * Fixed

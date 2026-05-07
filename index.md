---
layout: single
title: "Visual System Test"
author_profile: true
---

## Typography & Color Contrast Test

This page verifies the Serif/Sans-Serif split, BC Maroon accent, and off-white surface system before any content migration begins.

### Heading Hierarchy (Serif — Merriweather)

This `h3` and the `h2` above should appear in **Merriweather serif**. The paragraph text you are reading now should be in **Inter sans-serif**. The contrast between academic serif headings and modern sans-serif body text is the core typographic identity of this site.

#### h4 heading — also serif

Body text sits below this h4. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.

### Link & Accent Color Test

This is a paragraph containing [an inline text link](#) that should render in **BC Maroon `#8a100b`** with a subtle underline on hover. A second [example link](#) confirms consistency. Visited links should hold the same maroon rather than shifting to a browser default purple.

### Button Test

<a href="#" class="btn btn--primary">Primary Button (Maroon)</a>
<a href="#" class="btn btn--inverse">Secondary Button (Inverse)</a>

### Long-Form Readability

Proin vel tortor at mauris pharetra malesuada. Phasellus euismod diam at urna luctus, vel pretium mi cursus. Integer facilisis purus quis augue tincidunt, vel volutpat odio congue. Nam condimentum erat et est consequat, vel pretium erat vulputate. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae.

Donec condimentum dolor sit amet eros fermentum, vel tincidunt lacus condimentum. Nunc vulputate est a mi ornare mollis. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Suspendisse potenti.

### Inline Code & Mono

Inline code like `bundle exec jekyll build` should render in JetBrains Mono. The background color contrast should be clearly legible against the off-white `#FAFAFA` canvas.

```scss
// Example code block — verify monospace font and syntax highlight
$primary-color: #8a100b;  // BC Maroon
$background-color: #fafafa;  // warm off-white
```

---

*End of visual test. Verify: (1) Merriweather headings, (2) Inter body, (3) Maroon links and buttons, (4) off-white background visible against white browser chrome, (5) sidebar pills render correctly.*

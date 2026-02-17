# Intel Sustainability Journey

An interactive webpage presenting Intel's sustainability history and goals through a scrollable timeline, responsive layouts, and accessible design.

## Features

**Timeline** — A horizontal, scroll-snapping timeline on desktop and a single-column layout on mobile. Cards reveal their descriptions on hover, with staggered scroll-reveal animations driven by Intersection Observer.

**Responsive Layout** — Built with a combination of custom CSS flexbox and Bootstrap 5's grid system. Includes a three-column Commitments section, a subscription form, and a multi-column footer.

**RTL and Localization** — CSS logical properties (`padding-inline`, `inset-inline-start`) and Bootstrap's RTL build ensure the layout adapts to right-to-left languages. A JavaScript language detection system uses two MutationObservers to watch for language changes and automatically switches the page direction and Bootstrap stylesheet between LTR and RTL builds.

**Accessibility** — Skip link, semantic landmarks (`main`, `nav`, `footer`), descriptive alt text on all images, WCAG AA-compliant color contrast, and a fully labeled subscription form with `fieldset`/`legend` grouping for checkboxes.

**Interactivity** — A Bootstrap accordion FAQ section covers Intel's key sustainability topics. A hero auto-slideshow cycles background images every five seconds.

## Stack

- HTML, CSS, JavaScript
- Bootstrap 5
- Google Fonts (Nunito Sans)

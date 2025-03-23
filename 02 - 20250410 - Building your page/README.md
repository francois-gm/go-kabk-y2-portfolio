# Building your page

We will work from a simple HTML template that covers the essentials.

> Small note: A `script.js` has been addded at the end of the HTML document to illustrate how to potentially add JavaScript, if you have no need for JavaScript, you can remove the `script.js` as well as remove the `<script>` tags in the HTML documents.

### Core focus

- **Semantic markup** (`nav`, `section`, `figure`, etc.), improving structural readability
- **CSS variables**, making it easy to configure things once and reuse across stylesheet
- **CSS Grid**, flexible multi-column layouts
- **Media queries**, responsive design for any device

### Table of contents

- [Portfolio website](#portfolio-website)
    - [Core focus](#core-focus)
    - [Table of contents](#table-of-contents)
    - [Map structure](#map-structure)
  - [Web typography](#web-typography)
  - [Preparing media for online use](#preparing-media-for-online-use)
    - [Images](#images)
    - [Videos](#videos)
  - [How to take it further](#how-to-take-it-further)
  - [Getting your website online](#getting-your-website-online)
    - [Domain](#domain)
    - [Hosting](#hosting)
    - [Hosting companies \& domain providers](#hosting-companies--domain-providers)
  - [Portfolio inspiration](#portfolio-inspiration)
  - [Website tutorials](#website-tutorials)

### Map structure

```
assets/
├── fonts/             (contains all web-friendly font files, i.e. woff or woff2)
|   └── authentic-sans-90.woff
├── scripts/           (contains all JavaScript scripts)
|   └── script.js
└── stylesheets/       (contains all CSS stylesheets)
|   └── style.css
└── favicon.png        (the icon shown in the browser's tab)
work/                  (contains all projects)
├── project-title-a/   (folder renamed to the project's title in lowercase and with all spaces replaced as dashes)
|   ├── media/         (the project's media, i.e. images, videos, and audio)
|   └── index.html     (the project's HTML page)
index.html             (the homepage's HTML page)
```

## Web typography

Web fonts are specific files (.woff or .woff2) which you can use in CSS to use on your website. There are many free-to-use fonts for on the web and also a tool to convert other font files (.ttf, otf) to web font files with [Font Squirrel](https://www.fontsquirrel.com) or [Transfonter](https://transfonter.org) but keep in mind that font licenses are specific to the usage. So if you buy a print or desktop license for a font you're not allowed to use it online unless you buy the web license as well.

(see web font ressources last class for free and open-source type foundry options)

## Ingredients to play with (in the stylesheet)

- Change the color scheme.
- Add [borders](https://www.w3schools.com/css/css_border.asp), funky [underlines](https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-style), decorative elements like [outlines](https://www.w3schools.com/css/css_outline.asp) or [shadows](https://www.w3schools.com/css/css3_shadows.asp)?
- Change the typeface, use two typefaces (one for headings and one for paragraphs?), review its sizing (more contrast between heading and paragraph, or less contrast?).
- Change the layout (column sizes) while keeping the HTML markup.
- Add CSS 'hover' transition effects.
- Use CSS [filters](https://developer.mozilla.org/en-US/docs/Web/CSS/filter) or [mix-blend-mode](https://developer.mozilla.org/en-US/docs/Web/CSS/mix-blend-mode) on images?
- Add [CSS transitions](https://www.w3schools.com/css/css3_transitions.asp), [CSS animations](https://www.w3schools.com/css/css3_animations.asp), [CSS transforms](https://developer.mozilla.org/en-US/docs/Web/CSS/transform), or a bit of all of that?
- Add rounded corders with [border-radius](https://developer.mozilla.org/en-US/docs/Web/CSS/border-radius).
- Change margin and padding values.
- Add a background image, video or [CSS gradient](https://cssgradient.io)?

## How to take it further

- [How to - Portfolio Gallery with Filtering](https://www.w3schools.com/howto/howto_js_portfolio_filter.asp)
- [How to - Mobile Navigation Menu](https://www.w3schools.com/howto/howto_js_mobile_navbar.asp)
- [How to - Image Gallery](https://www.w3schools.com/howto/howto_js_tab_img_gallery.asp)
- [How to - Fullscreen Video](https://www.w3schools.com/howto/howto_css_fullscreen_video.asp)
- [How to - Popup/Modal](https://www.w3schools.com/howto/howto_css_modals.asp)
- [How to - Scroll Progress Indicator](https://www.w3schools.com/howto/howto_js_scroll_indicator.asp)
- [How to - Smooth Scroll](https://www.w3schools.com/howto/howto_css_smooth_scroll.asp)
- [How to - Custom Scrollbar](https://www.w3schools.com/howto/howto_css_custom_scrollbar.asp)
- [How to - Draggable HTML Elements](https://www.w3schools.com/howto/howto_js_draggable.asp)

## Website tutorials

- [Create a Free Website](https://www.w3schools.com/spaces/index.html)
- [Build a Website with HTML, CSS, and GitHub Pages](https://www.codecademy.com/learn/paths/learn-how-to-build-websites)
- [How to Make a Website with NameCheap](https://www.codecademy.com/learn/make-a-website)
- [How to Deploy a Website](https://www.codecademy.com/learn/deploy-a-website)

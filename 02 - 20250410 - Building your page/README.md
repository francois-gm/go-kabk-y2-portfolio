# Building your page

We will work from a simple HTML template that covers the essentials.

> Small note: A `script.js` has been addded at the end of the HTML document to illustrate how to potentially add JavaScript, if you have no need for JavaScript, you can remove the `script.js` as well as remove the `<script>` tags in the HTML documents.

### Core focus

- **Semantic markup** (`nav`, `section`, `figure`, etc.), improving structural readability
- **CSS variables**, making it easy to configure things once and reuse across stylesheet
- **CSS Grid**, flexible multi-column layouts
- **Media queries**, responsive design for any device

### Map structure

```
assets/
├── fonts/
|   └── authentic-sans-90.woff
├── js/
|   └── script.js
└── css/
|   └── style.css
└── favicon.png
projects/
├── project-title-a/
|   ├── media/
|   └── index.html
index.html
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

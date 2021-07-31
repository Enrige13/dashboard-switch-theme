# dashboard-switch-theme
https://www.youtube.com/watch?v=iL4irerdGdU&list=WL&index=62
# Functional Requirements and Notes

Light/Dark Mode toggle
-- takes system pref by default, but can override with toggle
-- https://dev.to/ananyaneogi/create-a-dark-light-mode-switch-with-css-variables-34l8

What HTML markup (accessible) 
-- https://scottaohara.github.io/a11y_styled_form_controls/src/radio-button--switch/

Use fieldset, legend, radio inputs

Switching between light/dark mode via JS and Prefers-color-scheme media query
-- https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-color-scheme
-- https://developer.mozilla.org/en-US/docs/Tools/Page_Inspector/How_to/Examine_and_edit_CSS#view_media_rules_for_prefers-color-scheme

Three option toggle: light/dark/system pref 
-- https://codepen.io/renddrew/pen/bRomab

CSS Variables (custom properties) 
-- https://css-tricks.com/updating-a-css-variable-with-javascript/
-- https://designcise.com/web/tutorial/how-to-update-a-css-variable-using-javascript

Accessibility
- Use correct heading tags
- Screenreader-only text for card titles/username
-- https://www.accessibility-developer-guide.com/
-- https://www.accessibility-developer-guide.com/examples/hiding-elements/visually/
-- https://www.accessibility-developer-guide.com/examples/forms/good-example/

-- https://accessible360.com/accessible360-blog/use-aria-label-screen-reader-text/



gulp global: npm install gulp-cli -g
package.json: npm init -y
auto prefixer: npm install @babel/core @babel/preset-env postcss autoprefixer browser-sync cssnano dart-sass gulp gulp-babel gulp-postcss gulp-sass gulp-terser


gulp



Error: Cannot find module 'sass'
npm cache clear
npm install sass
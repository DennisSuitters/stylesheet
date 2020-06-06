## {stylesheet}

the Minimal HTML5 mostly classeless Stylesheet v0.8

No SASS, No LESS, just plain good 'ol CSS.

We've made this stylesheet for AuroraCMS as a starting point for theme development. We were originally using Bootstrap, and it is still possible to do that, but we wanted something smaller, faster and easier to implement. You may notice though, a lot of the styling for elements is similar to Bootstrap 4, mainly colouring.

While the majority of the styling is similar to a css reset, the styling is mostly done to the elements as much as we can without classes, and unlike other bulky Frameworks (looking at you Bootstrap, Foundation, Tailwind), we style directly into the CSS Reset making styling similar but without the bloat. We have a Reset, then declare styling on the same elements without repeating again when it can all be done once.

Some things we take into account:
- Responsiveness.
- Cleanliness.
- Cross-Browser styling.
- Text Ledgibility (Text sizing for easy reading).

We decided to seperate the Extra's from the main stylesheet for those that don't want, or would like to build their own extra components, or only include the components needed.

Extra's that use `role="[name]"`, `data-content="[name]"` or classes to add features (Note: No Javascript is used, except for the Dialog which requires a Polyfill for Browsers that don't yet support Dialogs/Modals):
- Mobile Collapse Navigation `role="menubar"`
- Breadcrumbs `class="breadcrumb"`
- Covertron `class="covertron"`
- Jumbotron `class="jumbotron"`
- Slidertron `class="slidertron"`
- Tabs `class="tabs"`
- Alerts `class="alert"` or `class="alert alert-(danger/success/warning)"` for alert types.
- 360 Viewer `class="viewer360"`
- Comparison Slide `class="comparison"`
- Dialog, native to Chrome, but as a Polyfill for other browsers, instructional links are in the example file.
- Tooltips `data-tooltip="[top|right|bottom|left]"`

## CHANGELOG:
#### v0.8
- Tidy up example markup.
- Add Dark Mode styling and toggle option.
- Fix Checkbox and Radio button sizing.
- Fix Responsive Navigation Menu so it works better.
- Add Form Required, Valid, and Invalid styling.
- Seperate block and inline styling, Typography, and Extra Components into their files.
- Add CONTRIBUTING file to indicate how to format stylesheets.

#### v0.7
- Add more widgets, 360 Viewer, Comparison Slider, Add to documentation.

#### v0.6
- Adjust some features to use Classes to be more close to other libraries such as Bootstrap.
- Edit documentation.
- Fix Menu Dropdown z-index and white-space.

#### v0.5
- Add Tooltips
- Start adding code snippets to example file

#### v0.4
- Fix Typo's
- Add Dialog styling and instructional links on using a polyfil for browsers that don't yet support the element

#### v0.3
- Fix Tab styling
- Add Table zebra
- Adjust :root vars to better reflect their used
- Add Breadcrumb Styling
- Change Responsive Menu to use proper role value.

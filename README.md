![stylesheet](img/stylesheet.png) v0.4

the Minimal HTML5 mostly classe-less Stylesheet

No SASS, No LESS, just plain good 'ol CSS.

We've made this stylesheet for AuroraCMS as a starting point for theme development. We were originally using Bootstrap, and it is still possible to do that, but we wanted something smaller, faster and easier to implement. You may notice though, a lot of the styling for elements is similar to Bootstrap 4, mainly colouring.

While the majority of the styling is similar to a css reset, the styling is mostly done to the elements as much as we can without classes.

Some things we take into account:
- Responsiveness.
- Cleanliness.
- Cross-Browser styling.
- Text Ledgibility (Text sizing for easy reading).

Extra's that use `role="[name]"`, `data-content="[name]"` or classes to add features (Note: No Javascript is used):
- Mobile Collapse Navigation `role="menubar"`
- Breadcrumbs `data-content="breadcrumb"`
- Covertron `data-content="covertron"`
- Jumbotron `data-content="jumbotron"`
- Slidertron `data-content="slidertron"`
- Tabs `data-content="tabs"`
- Testimonials section `data-content="testimonials"`
- Alerts `data-content="alert"` or `data-content="alert-(danger/success/warning)"` for alert types.
- Dialog, native to Chrome, but as a Polyfill for other browsers, instructional links are in the example file.

TODO: (Pull Requests Welcome)
- Accordian

## CHANGELOG:
#### v0.4
- Fix Typo's
- Add Dialog styling and instructional links on using a polyfil for browsers that don't yet support the element

#### v0.3
- Fix Tab styling
- Add Table zebra
- Adjust :root vars to better reflect their used
- Add Breadcrumb Styling
- Change Responsive Menu to use proper role value.

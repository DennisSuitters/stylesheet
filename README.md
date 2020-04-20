![stylesheet](img/stylesheet.png) v0.2

the Minimal HTML5 mostly classless Stylesheet

We've made this stylesheet a base for AuroraCMS as a starting point for theme development. We were originally using Bootstrap, and it is still possible to do that, but we wanted something smaller, faster and easier to implement.

While the majority of the styling is similar to a css reset, the styling is mostly done to the elements as much as we can without classes.

Some things we take into account:
- Responsiveness.
- Cleanliness.
- Cross-Browser styling.
- Text Ledgibility (Text sizing for easy reading).

Extra's that use `role="[name]"`, `data-content="[name]"` or classes to add features (Note: No Javascript was used):
- Mobile Collapse Navigation `role="mobile-menu"`
- Covertron `data-content="covertron"`
- Jumbotron `data-content="jumbotron"`
- Slidertron `data-content="slidertron"`
- Tabs `data-content="tabs"`
- Testimonials section `data-content="testimonials"`

TODO: (Pull Requests Welcome)
- Accordian
- Alerts
- Breadcrumbs
- Dialogs

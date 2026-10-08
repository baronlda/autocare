# AutoCare

[Public website](https://baronlda.github.io/autocare/) · [English version](https://baronlda.github.io/autocare/?lang=en)

A bilingual Ukrainian / English auto workshop portfolio demonstration.

## Design and experience

The website is built around a car and a service enquiry, with an interactive schematic on the first screen. A warm paper palette, lime accents, large typography and workshop document details run through the whole page.

- Interactive car diagram and six service selectors linked to the enquiry.
- Filtered service directory with expandable rows.
- Workshop photograph and work order showing four repair stages.
- Single large review with previous / next navigation. Reviews are clearly marked as fictional examples.
- Two-step enquiry form: vehicle details, then contact details, then a demo confirmation. The side panel reflects entered vehicle and chosen service.
- Telegram draft creation and copying, expandable FAQ, mobile navigation, keyboard support and reduced motion.
- Language switching preserves form values, wizard step, review, chosen service, filters and open content.

## Source

`index.html` loads `content.js` (bilingual content), `app.js` (rendering and interactions) and `styles.css`. `hero.png` is an original generated illustration of a workshop. The earlier `sections.css` is retained as an unused historical asset; the current website does not load it.

Static HTML/CSS/JavaScript, no dependencies and no build. GitHub Pages publishes `main` from the repository root.

## Demonstration

AutoCare is a fictional brand. There is no actual workshop address, real client review, live appointment time, or receiving endpoint. Form details are not sent or persisted. Telegram creates a local draft, not a message to a connected recipient. The diagram selects a service and does not diagnose faults.

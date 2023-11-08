# GOV.UK Prototype Kit plugin for the Scottish Government Design System

This is an unofficial fork of the [Scottish Government Design System](https://github.com/scottish-government-design-system/design-system) updated to work as a plugin for the [GOV.UK Prototype Kit](https://github.com/alphagov/govuk-prototype-kit).

## Usage

Once you have a version of the Prototype Kit installed,
- open a terminal window at that folder and run `npm i scotgov-prototype-plugin`
- create a `settings.scss` file in `app/assets/sass` and add `$govuk-global-styles: false;` to it
- open `app/views/layouts/main.html` and change the line `{% extends "govuk-prototype-kit/layouts/govuk-branded.njk" %}` to `{% extends "/scotgov-prototype-plugin/scotgov-template.njk" %}`

# GOV.UK Prototype Kit plugin for the Scottish Government Design System

This is an unofficial fork of the [Scottish Government Design System](https://github.com/scottish-government-design-system/design-system) updated to work as a plugin for the [GOV.UK Prototype Kit](https://github.com/alphagov/govuk-prototype-kit).

## Usage

Once you have a copy of the Prototype Kit installed,
1. open a terminal window at that folder and run **npm i scotgov-prototype-plugin**
2. run **npm run dev** as usual
3. create a **settings.scss** file in **app/assets/sass** and add **$govuk-global-styles: false;** to it
4. in the browser, navigate to the **Manage your prototype** section and go to **Templates**
5. create the required main layout at **/layouts/scotgov-main**
6. create and use one of the other templates as a basis for your prototype.
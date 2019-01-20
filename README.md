# CSS is !important - Challenge One: Benchmarking
A benchmarking test to test your CSS skills.
The aim is to create this:

![CSS is !important](screenshot.jpg)

See high-res screenshot - https://raw.githubusercontent.com/css-is-important/challenge-one/master/screenshot-high-res.png
## Challenge notes
- The page header should be fixed
- The page header has a red border and a shadow
- The main page feature has a dark overlay on the image
- The main title has a text shadow
- The image next to the italic text (on the red gradient background) has an inner and outer shadow
- The red gradient should run from the primary color (`$red`) down to the secondary (`$orange`)
## The Rules
There's really only one rule to this: *You may not edit the HTML*

You can add classes, but the structure of the HTML must not change.

Actually there is another rule... Everything you do must be done in CSS. No javascript should be used aside from what's there.
## Running the repo
- If you don't already have grunt.js on your computer, run `npm install -g grunt-cli`
- Clone the repo to your computer
- Run `npm install`
- Run `grunt`
- The page will run at `localhost:9000`
## Taking part
- Create a `entries/your-name` branch from `master`
- Follow https://github.com/BennyHudson
- You will be added as a contributor to the `css-is-important` organisation
- Write your best CSS
- Push your branch
- Profit
## Things to note
- There may be some `id`s in the HTML. These are purely for javascript and should not be changed.
- Colours are predefined and are available inside `stylesheets/dev/colours.scss`
- Spacing values are not provided. You may choose a suitable value, as long as it is consistent across the page - don't worry about pixel-perfection.
- Treat this as a real, content-driven website - don't make things too specific!
## Helpers
- Font Awesome Pro is included in this project
- There are some predefined mixins that may come in handy. These can be found in `stylesheets/dev/mixins.scss`
- The default browser styles have been disabled with `stylesheets/dev/reset.scss`
- _Very_ basic styles have been added to `stylesheets/dev/global.scss` to get you started
- A basic build of Modernizr has been added for cross browser testing. If you need more, create your own at https://modernizr.com/
## Browsers, Devices & Extras
- Your code should work consistently across all modern browsers
- You should give consideration to responsive design. Desktop first media queries are included inside `stylesheets/dev/media.scss`
- Mobile screenshots are not provided. Just do what feels right
## Further reading & useful tools
- https://css-tricks.com/snippets/css/a-guide-to-flexbox/
- https://css-tricks.com/snippets/css/complete-guide-grid/
- https://css-tricks.com/box-sizing/
- http://css3generator.com/
- http://apps.eky.hk/css-triangle-generator/
- http://www.colorzilla.com/gradient-editor/
- https://fontawesome.com/

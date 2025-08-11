# sign-up-form

A basic sign-up form for a fictional service, created using my knowledge of HTML & CSS thus far. 

<strong>Features:</strong> This webpage features a left side with image banner and logo, and a right side with a registration form. There is some responsiveness implemented for different window sizes and zoom levels. Accessibility features were implemented when filling out the form, including custom focus indicators and error messages. Webpage was tested on Chrome & Firefox. 

<strong>Caveats:</strong> The following were out of scope for this project: No responsiveness for mobile/other devices. No Javascript validation for the form. Did not test on all major browsers. Limited custom styling for checkboxes (due to basically needing to build Rome from scratch for them). Other form controls were omitted: radio, select. 

## New concepts used
- svg
- css normalization/reset
- css properties including text styles & shadows, positioning, custom font
- custom css properties
- advanced selectors: siblings & descendents, psuedo-class & elements
- responsive design: relative units, min/max functions & properties 
- basic accessibility (following the Accessibility section on each MDN documentation)
- basic testing for browser compatibility
- devtools state testing
- form semantics, style, & validation

## Reflection
So many concepts. At first I was overwhelmed with how many concepts I was tasked with practicing/implementing, but I tackled them one at a time in a sensible order. 

This project introduced some new things to test for during development: responsiveness and browser compatibility. I created some basic responsiveness with relative units and min/max/clamp. I tested with Firefox — in the future I can consider browser emulators to test other browsers. 

I would like feedback on the HTML semantics and how I styled the form controls including their interactive components. 

Time spent: about 20 hours.

## Sources of help
These are helpful threads I consulted for help over the course of developing this project. Note that most documentation I looked at is omitted due to how many I look at. 
- [Freecodecamp thread: when to use 'main' tag](https://forum.freecodecamp.org/t/what-is-main-tag-used-for-i-dont-understand-at-all/381898/2)
- [Stackoverflow: adding space between list items](https://stackoverflow.com/a/63890844/22151685)
- [Stackoverflow: border vs outline for focus state](https://stackoverflow.com/questions/3397113/how-to-remove-focus-border-outline-around-text-input-boxes-chrome)
- [Stackoverflow: outline-color compatibility in Firefox](https://stackoverflow.com/questions/67667161/is-css-outline-color-property-is-not-working-in-firefox-e-g-inputfocus-ou)
- [Stackoverflow: text overflow in span element](https://stackoverflow.com/questions/41126157/overflow-x-text-overflow-in-span)
- [Odin Project Community: on testing browser compatibility](https://discord.com/channels/505093832157691914/505093832157691916/1404572788454326418)

## Assets used
- [Logo font - Poiret One from fonts.google.com](https://fonts.google.com/specimen/Poiret+One?preview.text=Good%20Thought&categoryFilters=Feeling:%2FExpressive%2FCalm)
- [Background photo - by Bertvthul on Pixabay](https://pixabay.com/photos/avenue-trees-path-sunbeams-sunrays-815297/)
- [Logo image - supplied by SVG Viewer](https://www.svgviewer.dev/s/446953/sunflower)
- Some snippets from [Modern Normalize](https://github.com/sindresorhus/modern-normalize) 
# Accessible Dark Mode Toggle Button

- [Website (Git Pages)](https://chrisnajman.github.io/accessible-dark-mode-toggle-button)

## Description

An accessible dark mode toggle button employing `ARIA` attributes for screen reader users.

Additionally, visual cues (icon, on/off text) are provided for sighted users.

## Accessibility

- The `ARIA-pressed` attribute indicates the button state to screen readers.
- The `ARIA-hidden` attribute hides the SVG icon and CSS `content` text from screenreaders.
- Keyboard navigation via the `Tab` key focuses the button.

## CSS

- CSS variables are used for the dark and light themes.
- The `content` property prints 'on' or 'off' according to the state of the button.

## Javascript

- Button state is saved to local storage, so the chosen theme persists.
- ES6 (no transpilation to ES5)

## Sources

- ['Moon' icon from Free Box Icons (click SVG tab for code))](https://boxicons.com/?query=Moon)
- [`ARIA-pressed` information (and more) from Inclusive Components/Toggle Buttons](https://inclusive-components.design/toggle-button/)

## Testing

- Tested on:
  - Windows 10
    - Chrome
    - Firefox
    - Microsoft Edge

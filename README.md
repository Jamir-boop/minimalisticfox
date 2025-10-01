# MinimalFox User Style for Firefox ESR

MinimalFox is a minimalist user style focused on reducing screen clutter and emphasizing simplicity and usability.

<p align="center">
  <img src="icon.png" alt="MinimalFox Icon" width="100" height="100">
</p>

_*This was written mainly for [Firefox ESR](https://support.mozilla.org/en-US/kb/choosing-firefox-update-channel). but it can also work on standard versions._

https://github.com/Jamir-boop/minimalisticfox/assets/73477811/b2b9736d-6005-44cb-a219-358267869ad3

## Prerequisites

- Firefox ESR Browser (recommended, might with standard versions too).
- Font [Cascadia Code](https://github.com/microsoft/cascadia-code/releases/) installed on your system.
- Knowing the basic shortcuts to close/open tabs (ctrl+w, ctrl+t) The more you know the better.

## Enabling userChrome.css in Firefox

1. Open Firefox and type `about:config` in the address bar. Press Enter.
2. Click "Accept the Risk and Continue" if prompted.
3. Search for `toolkit.legacyUserProfileCustomizations.stylesheets` and set it to `true` by clicking the toggle button.
4. Search for `browser.compactmode.show` and set it to `true` by clicking the toggle button.
5. Set toolbar density to `compact`
<img src="https://i.ibb.co/dPRFWb2/image.png" alt="image" border="0" width="300px">
6. (Optional) Disable tab previews: set `browser.tabs.hoverPreview` to `false`.

## Installation

1. Open Firefox and go to your profile root folder (via `about:profiles`).
2. Create a folder named `chrome` if it doesn’t exist.
3. Copy the `userChrome.css` file from this repo into the `chrome` folder.
4. Restart Firefox.
5. At `about:preferences` Set your default font to Cascadia Code
  <img src="https://i.ibb.co/0JvVP6Y/image.png" alt="image" border="0" width="100%">

### Note on the screenshots

This style is compatible with any theme, the one that I'm using the [Dark Space](https://github.com/nicoth-in/Dark-Space-Theme) theme.

## CSS Customizations Included

The provided CSS code makes several modifications to streamline the Firefox UI:

- Hides the navigation bar by default, showing it only when the `navigator-toolbox` is hovered over or focused.
- Adjusts tab appearance for minimalism.
- Hides various UI elements like the tab close button and title bar buttons for a cleaner look.
- Extension menu shown in cleaner way.
- Optionally you can set the font to "Cascadia Code" across the UI for consistency and readability (If you have it installed).

## Conclusion

MinimalFox aims to offer a cleaner, more focused browsing experience by minimizing UI distractions. Remember, custom user styles like this are subject to break with future Firefox updates, so adjustments may be necessary over time.

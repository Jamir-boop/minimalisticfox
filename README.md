# MinimalFox User Style for Firefox

MinimalFox is a minimalist user style for Firefox, focusing on reducing screen clutter and emphasizing simplicity and usability.

<p align="center">
  <img src="icon.webp" alt="MinimalFox Icon" width="100" height="100">
</p>


https://github.com/Jamir-boop/minimalisticfox/assets/73477811/b2b9736d-6005-44cb-a219-358267869ad3


## Prerequisites

- Firefox Browser
- A userChrome.css file enabled (see instructions below on how to enable)

## Enabling userChrome.css in Firefox

1. Open Firefox and type `about:config` in the address bar. Press Enter.
2. Click "Accept the Risk and Continue" if prompted.
3. Search for `toolkit.legacyUserProfileCustomizations.stylesheets` and set it to `true` by clicking the toggle button.
4. Restart Firefox for the change to take effect.

## Installation

1. Open your Firefox profile directory:
   - On Windows, press `Win+R`, type `%APPDATA%\Mozilla\Firefox\Profiles`, and press Enter.
   - On macOS, open Finder, press `Command+Shift+G`, enter `~/Library/Application Support/Firefox/Profiles`, and press Enter.
   - On Linux, the path is usually `~/.mozilla/firefox/`.
2. Open the profile folder (it may look like `xxxxxx.default-release`).
3. Create a folder named `chrome` if it doesn't already exist.
4. Inside the `chrome` folder, create a file named `userChrome.css` if it doesn't already exist.
5. Paste the `userChrome.css` file provided on this repo.

### Note on the screenshots

This style is usable in with any theme, the one that Im using is [Dark Space](https://github.com/nicoth-in/Dark-Space-Theme).

## CSS Customizations Included

The provided CSS code makes several modifications to streamline the Firefox UI:

- Hides the navigation bar by default, showing it only when the `navigator-toolbox` is hovered over or focused.
- Adjusts tab appearance for minimalism.
- Hides various UI elements like the tab close button and title bar buttons for a cleaner look.
- Optionally you can set the font to "CaskaydiaCove NF" across the UI for consistency and readability (If you have it installed).

## Conclusion

MinimalFox aims to offer a cleaner, more focused browsing experience by minimizing UI distractions. Remember, custom user styles like this are subject to break with future Firefox updates, so adjustments may be necessary over time.

Enjoy your cleaner, more minimalist Firefox experience with MinimalFox!

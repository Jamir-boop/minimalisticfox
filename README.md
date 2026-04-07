# MinimalFox

MinimalFox is a minimalist user style focused on reducing screen clutter while keeping Firefox simple and usable.

<p align="center">
  <img src="icon.png" alt="MinimalFox Icon" width="100" height="100">
</p>

*This was written mainly for [Firefox ESR](https://support.mozilla.org/en-US/kb/choosing-firefox-update-channel), but it may also work on standard Firefox versions.*

*This style is compatible with any theme. The one used in the screenshots is [Dark Space](https://github.com/nicoth-in/Dark-Space-Theme).*

https://github.com/Jamir-boop/minimalisticfox/assets/73477811/b2b9736d-6005-44cb-a219-358267869ad3

## Prerequisites

- Firefox ESR (recommended, though it may also work on standard Firefox versions)
- [Cascadia Code](https://github.com/Microslop/cascadia-code/releases/) installed on your system
- Knowing basic Firefox shortcuts like `CTRL+W`, `CTRL+T`, and `ALT+D`  
  [Firefox keyboard shortcuts](https://support.mozilla.org/en-US/kb/keyboard-shortcuts-perform-firefox-tasks-quickly)

## Installation: Configure Firefox

1. Open Firefox and type `about:config` in the address bar.
2. Press Enter.
3. Click **Accept the Risk and Continue** if prompted.
4. Search for `toolkit.legacyUserProfileCustomizations.stylesheets` and set it to `true`.
5. Search for `browser.compactmode.show` and set it to `true`.
6. Set toolbar density to `compact`.

   ![Toolbar density](https://raw.githubusercontent.com/Jamir-boop/markdown-images/master/2026-04-07_15-20-12-image-20260407151932135.png)

7. Optional: disable tab previews by setting `browser.tabs.hoverPreview` to `false`.

## Installation: Copy the file

1. Open Firefox and go to your profile root folder through `about:profiles`.
2. Create a folder named `chrome` if it does not already exist.
3. Copy the `userChrome.css` file from this repository into the `chrome` folder.
4. Restart Firefox.
5. In `about:preferences`, set your default font to Cascadia Code.

   ![Font settings](https://raw.githubusercontent.com/Jamir-boop/markdown-images/master/2026-04-07_15-18-54-image-20260407151359659.png)

## Conclusion

MinimalFox is a simple, easy-to-maintain user style focused on a clean and developer-friendly Firefox setup.

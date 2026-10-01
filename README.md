# MinimalFox

MinimalFox is a minimalist user style focused on reducing screen clutter while keeping Firefox simple and usable.

<p align="center">
  <img src="icon.png" alt="MinimalFox Icon" width="100" height="100">
</p>

*This was written mainly for [Firefox ESR](https://support.mozilla.org/en-US/kb/choosing-firefox-update-channel), but it may also work on standard Firefox versions.*

*This style is compatible with any theme. The one used in the screenshots is [Dark Space](https://github.com/nicoth-in/Dark-Space-Theme).*

[MinimalFox](https://github.com/Jamir-boop/minimalisticfox) owns toolbar reveal, compact tabs, browser chrome fonts, and the five-column extension grid and notification layout. In a combined setup, [Amber Black](https://github.com/Jamir-boop/amber-black) owns colors, background images, borders, focus, selection, carets, and about-page fonts.

https://github.com/user-attachments/assets/b31692f5-84b7-43a3-9ebf-dbd563a5c6f7

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

## Installation with Amber Black

Keep the prerequisites, Firefox configuration, and font settings above. For the combined setup, use these file-copy steps:

1. Copy this repository's `userChrome.css` as `<profile>/chrome/minimalFox.css`.
2. Copy [Amber Black](https://github.com/Jamir-boop/amber-black)'s `firefox/userChrome.css`, `firefox/userContent.css`, and `firefox/img/` into the same `chrome` folder under their original names.
3. Restart Firefox.

Amber's `userChrome.css` imports the local `minimalFox.css` first. Its appearance rules then override MinimalFox's defaults. Keep one `userChrome.css` and one `minimalFox.css`; all CSS files stay local to the profile. The standalone installation above still uses MinimalFox directly as `userChrome.css`.

## Conclusion

MinimalFox is a simple, easy-to-maintain user style focused on a clean and developer-friendly Firefox setup.

# Changelog

## v0.3.7 (7 March 2020)

- Hide and center cursor position in scroll-area in Scroll-mode
- Revert cursor position upon existing Scroll-mode
- Show hints for extra menu-bar items
- (Experimental) Add option to force keyboard layout
- Add option to launch on startup

## v0.3.6 (27 Jan 2020)

- Show hints only for actionable elements.
- Show prompt for granting Accessibility permission.
- Allow shortcut to exit hint/scroll mode.
- Add menu bar icon.

## v0.3.5 (3 Jan 2020)

- Bind Shift + HJKL to scroll by half of scroll area vertically / horizontally.
- Keep hint text consistent when element tree is unchanged.

## v0.3.4 (25 Dec 2019)

- Use TAB key to cycle through scroll areas in Scroll mode instead of using hints to select them.
- Lock cursor in position in Scroll mode.

## v0.3.3.1 (24 Nov 2019)

- Reverse D and U keys scroll direction when vertical scroll is reversed. Oops!

## v0.3.3 (23 Nov 2019)

- Configure vertical and horizontal scroll direction in Preferences.
- Fix right-click not working on some elements.

## v0.3.2 (18 Nov 2019)

- Fix hint positioning when using multiple displays
- Fix hints appearing with white text

## v0.3.1 (3 Nov 2019)

- Position hints in the center of elements instead of top-left
- Improved hint-showing performance
- Allow ESC to quit Scroll mode
- Remove Chromium support because it breaks window positioning with window managers

## v0.3.0 (23 Oct 2019)

- Removed "commands". Use CTRL+SPACE to enter Hint Mode and CTRL+S to enter Scroll Mode.
- Hold SHIFT while typing hints to right click. Hold CMD while typing to double click.
- Tab key in Hint Mode cycles between all hints and hints for actionable elements.
- Added app icon. Thanks @liaujianjie!
- Removed Focus Mode.

## v0.2.3 (11 Oct 2019)

- Add Scroll Selector Mode (mapped to "s" and "ss") and change Scroll mode's command to "sh" (scroll here)
- Add Focus Mode (mapped to "f") for focusing on text fields
- Always show command popup instead of toggling it when the shortcut is activated
- Fix backspace not bring back deleted hints
- Add Chromium support (not including Electron)
- Make traversal asynchronous so the program doesn't freeze

## v0.2.2 (4 Oct 2019)

- Scroll mode now supports scrolling with D and U keys. They scroll by half the height of the scroll area.
- Filtering of hints by element role.
- Hints appear for static text elements again.
- Hints are bounded by the element's parent scroll area instead of the window.

## v0.2.1 (3 Oct 2019)

- Blacklisted some element roles so hints do not show up for them.

## v0.2 (29 Sep 2019)

- Added a scroll command ("s"). Use the HJKL keys after entering the command to scroll. Tip: Use "me" to move your cursor to a scroll area before entering scroll mode! Scroll area selection is WIP.

## v0.1.2 (29 Sep 2019)

- Improve element finding algorithm when dealing with AXPage elements (e.g. PDFs in Preview)
- Show hints for AXPage / AXRows that are partially in the window's frame, instead of only those whose origin (top-left corner) lie in the window's frame.

## v0.1.1

- Fix click event not being recognized by certain apps (App Store).

## v0.1.0

- First release!

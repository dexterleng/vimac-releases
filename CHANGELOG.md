# Changelog

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

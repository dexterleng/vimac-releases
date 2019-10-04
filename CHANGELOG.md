# Changelog

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

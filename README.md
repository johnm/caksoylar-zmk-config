# zmk-config

This is a [ZMK](https://zmk.dev) config repo for my 36 key [Corne-ish Zen](https://lowprokb.ca/products/corne-ish-zen), arranged in 3 rows of 5 columns with 3 thumb keys on each side (where I mostly don't use the tuckiest thumbs). It uses three non-base layers activated through two thumb keys along with combos. It has <kbd>Ctrl</kbd>/<kbd>Shift</kbd> thumb hold-taps along with home row mods, which are also available on the left side of `NAV` layer. `FUN` layer is implemented as a tri-layer (active when both `NAV` and `SYM` are active).

OS-dependent shortcuts are present on the `NAV` layer, e.g. for Windows:
- `Win Close`: <kbd>Alt</kbd><kbd>F4</kbdy>
- `Tab Next`: <kbd>Ctrl</kbd><kbd>Tab</kbd>
- `Tab Prev`: <kbd>Ctrl</kbd><kbd>Shift</kbd><kbd>Tab</kbd>
- `Tab Close`: <kbd>Ctrl</kbd><kbd>F4</kbd>
- `Desk Next`: <kbd>Ctrl</kbd><kbd>Gui</kbd><kbd>Right</kbd>
- `Desk Prev`: <kbd>Ctrl</kbd><kbd>Gui</kbd><kbd>Left</kbd>
- `Win Next`: <kbd>Alt</kbd><kbd>Tab</kbd> (hold Alt while layer active), not implemented in ZMK
- `Win Prev`: <kbd>Alt</kbd><kbd>Shift</kbd><kbd>Tab</kbd> (hold Alt while layer active), not implemented in ZMK

I also use a nifty mod-morph trick: While holding <kbd>Alt</kbd> on the left home row, tapping the backspace thumb emits <kbd>Tab</kbd> for one-handed window switching. <kbd>Alt</kbd><kbd>Backspace</kbd> can still be performed with the right hand modifier.

![3x5 layout](https://caksoylar.github.io/zmk-config/3x5.full.svg)

(Visualization generated with [@caksoylar/keymap](https://github.com/caksoylar/keymap))

See my [QMK userspace](https://github.com/caksoylar/qmk_userspace/) for equivalent keymap definitions for QMK.

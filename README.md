# Gothic Punk Equicord Themes 🖤💗

Three hot pink / magenta / neon green / purple / blood red gothic-punk themes for [Equicord](https://equicord.org/). Glowing headers, an animated gradient title bar, a black cursor with a colored underglow, and glittery unread badges — MySpace-core, but make it 2026.

Made by [@ad0rkableg33k](https://github.com/ad0rkableg33k).

## Themes

| Theme | Main color | File |
|---|---|---|
| **Gothic Punk** | Hot pink & magenta | [`themes/gothic-punk-pink-magenta.theme.css`](themes/gothic-punk-pink-magenta.theme.css) |
| **Neon Coven** | Neon green & purple | [`themes/neon-coven-green-purple.theme.css`](themes/neon-coven-green-purple.theme.css) |
| **Blood Coven** | Blood red, with glowing black body text | [`themes/blood-coven-red-black.theme.css`](themes/blood-coven-red-black.theme.css) |

All three share the same black background and the same set of effects:

- Glowing headers and channel titles
- Animated gradient title bar / tab strip
- Custom black cursor with a colored underglow (brighter glow on hover)
- Glittery, shimmering unread/mention badges
- Purple-glow channel & server list text, with member list names glowing in their own role color
- Pink/red/green-glow buttons, links, and message hover states

## Installation

1. Open Discord and go to **User Settings** (the gear icon next to your username).
2. Scroll down to the **Equicord** section in the sidebar and click **Themes**.
3. Click the **folder icon** ("Open Themes Folder") near the top of the page. This opens the local folder where Equicord loads `.theme.css` files from.
4. Download whichever theme file(s) you want from the [`themes/`](themes) folder above (click the file → **Download raw file**), and move them into that folder.
5. Back in Discord's Themes tab, the theme should now show up in the list (e.g. "ad0rkableg33k Gothic Punk"). Toggle it **on**.
6. Reload Discord (`Ctrl+R` / `Cmd+R`) if anything looks off.

You can install more than one theme at once — they won't conflict — and just toggle whichever one you're feeling on any given day.

## Notes

- These use `[class*="..."]` attribute selectors wherever possible instead of exact Discord class names, so they're more resistant to Discord's random hash updates than a lot of themes — but Discord *does* occasionally shuffle class names enough to break a selector. If something stops glowing after a Discord update, open an issue with a screenshot and I'll patch it.
- Built for desktop Equicord/Vesktop. Not tested on mobile.

## Cursor packs for Mac and Windows

Every theme's cursors are also available as standalone packs in [`cursors/mac-windows/`](cursors/mac-windows), with a cursor for every pointer type and a smaller 32px set if they look too big on your screen. All five are in [`all-mac-windows-packs.zip`](cursors/mac-windows/all-mac-windows-packs.zip).

**Mac** (macOS 15 Sequoia or newer): install [MaCursor](https://github.com/writronic/MaCursor), open it, choose **File > Convert Theme...**, pick the theme folder from the unzipped pack, then select the theme in the library and apply it.

**Windows:** unzip the pack, right-click `install.inf` in the theme folder and choose **Install**, then go to **Settings > Bluetooth & devices > Mouse > Additional mouse settings > Pointers**, pick the theme in the **Scheme** dropdown and click **Apply**. If the scheme doesn't appear, browse to the `.cur` files by hand: `Pointer.cur` is the arrow, `Link.cur` is hover and `Busy.cur` is loading.

## License

MIT — do whatever you want with these, just don't resell them as-is.

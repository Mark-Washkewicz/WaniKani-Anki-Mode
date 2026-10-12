# Wanikani Anki Mode

Anki-style self grading for WaniKani reviews and lesson quizzes: reveal the answer, then mark whether you knew it.

## About this fork

This is a fork of [JDurman/WaniKani-Anki-Mode](https://github.com/JDurman/WaniKani-Anki-Mode), maintained by [Mark Washkewicz (@Mark-Washkewicz)](https://github.com/Mark-Washkewicz).

JDurman's script stopped working after WaniKani changed its quiz pages, and it hasn't been updated since. This fork keeps it working. Changes are kept compatible with the original, so they can be merged back upstream if JDurman returns.

The original code is still available:

- Repository: [JDurman/WaniKani-Anki-Mode](https://github.com/JDurman/WaniKani-Anki-Mode)
- Last original release (3.0.12): [`wk_anki_mode.js` at `f45cf75`](https://github.com/JDurman/WaniKani-Anki-Mode/blob/f45cf75e1f093166742a186154ef58636203f864/wk_anki_mode.js)
- Original Greasy Fork listing: [Wanikani Anki Mode](https://greasyfork.org/scripts/437009)
- Discussion: [WaniKani Community thread](https://community.wanikani.com/t/userscript-anki-mode/54751)

## Changes since 3.0.12

- Works with WaniKani's current review and lesson quiz pages.
- Keeps working across multiple sessions without refreshing the page.
- Hotkeys no longer stop working at random after starting a session.
- Hotkeys no longer block the arrow keys on lesson slides after a lesson quiz.
- Anki mode no longer turns itself on because of an old saved setting.
- In lesson quizzes, click the answer box to type an answer yourself. Click outside it to go back to Anki mode.

## Installation

1. Install [Tampermonkey](https://www.tampermonkey.net/) (or another userscript manager).
2. Install the [WaniKani Open Framework](https://community.wanikani.com/t/instructions-installing-wanikani-open-framework/28549), which this script requires.
3. Install **Wanikani Anki Mode** from [Greasy Fork](https://greasyfork.org/en/scripts/599957-wanikani-anki-mode). It updates automatically from there.

Because the name and namespace match the original, this replaces an existing install of JDurman's version.

## Usage

- Click the star in the item header to turn Anki mode on or off.
- **Show Answer** (default: Space), then **Know** (default: 1) or **Don't know** (default: 2).
- Change hotkeys and other options under the WaniKani menu: Settings → Anki Mode.

## Credits

- [JDurman](https://github.com/JDurman): author of Wanikani Anki Mode 3.x.
- Mempo: original Wanikani Anki Mode script, with modifications by necul and irrelephant.
- Robin Findley (rfindley): the Double-Check script this one was templated on.
- Casinocas: [compatibility fix posted on the WaniKani Community forum](https://community.wanikani.com/t/userscript-anki-mode/54751/224), which this fork's first fix is based on.

## License

GPL version 3 or any later version. See [LICENSE](LICENSE).

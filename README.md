# Venture Steam art database

How Venture frames each Quest game's store cover as Steam library art. Meta's store has no portrait art, so [Venture](https://github.com/Villagers654/Venture) makes Steam's 600x900 capsule from the landscape cover.

`titles.json` is keyed by package name. Each entry is framed for one cover file, named by `cover_sha256`; a different cover (after a store update) gets the default. `zoom` 0 shows the whole cover across the capsule's width over a blurred fill, 1 fills the capsule's height, above 1 goes closer. `focus_x` and `focus_y` are the point of the cover the capsule centres on, from 0 to 1 (0.5 by default). A game without an entry gets zoom 0.

The first entries are by Joseph DiGiovanni. Missing or badly framed game? Open an issue with the game's name.

Data is CC0.

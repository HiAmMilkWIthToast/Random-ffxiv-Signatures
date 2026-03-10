# Random FFXIV Signatures

Useful FFXIV signatures for plugin developers, grouped by feature and kept readable.

Start with `CATEGORIES` to find the section you want, then search the main signatures file by `CATEGORY:`.

## Files
- `Signatures` — main signature list
- `CATEGORIES` — quick category index
- `README.md` — basic usage notes

## How To Use
Search broad topics with:
- `CATEGORY: PvP`
- `CATEGORY: Quest`
- `CATEGORY: Gold Saucer`
- `CATEGORY: Camera`

Then jump to the exact section you want in `Signatures`.

## Notes
- Signatures are organized for browsing first, not just raw dumping.
- Some sections are deeper than others depending on what was worth keeping.
- Always validate against the current client if you plan to use them in a plugin.

## Notes on Duplicates

This repo aims to keep each signature in one canonical category only.

If you spot:
- duplicate names
- duplicate signatures
- the same hook mirrored across multiple categories

it is usually accidental carry-over from older revisions, not intentional multi-placement.

Preferred rule:
- generic hooks live in their single best home
- subsystem-specific hooks stay in their subsystem
- packet handlers usually belong under `Network - ...` unless the subsystem placement is clearly better

## Credit
Created by jungle.

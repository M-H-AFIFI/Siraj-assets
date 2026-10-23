# Siraj assets

The files the Siraj app downloads: adhans, rare recitations, the Mushaf database, the page fonts and
the tafsir books. Free to use with the app; the recordings belong to their reciters.

## In this repository (27 files, 84.8 MB)

| Folder | Files | Size |
| --- | --- | --- |
| `audio/adhan/` | 9 | 8.9 MB |
| `audio/adhan/fajr/` | 5 | 7.4 MB |
| `audio/recitations/abdul-azim-zaher/` | 13 | 68.5 MB |

The app fetches these from jsDelivr (`https://cdn.jsdelivr.net/gh/<owner>/<repo>@main/<path>`), and
from GitHub's raw host if that fails. Keep every path and name as it is: the app builds its addresses
from them. `manifest.json` lists each file with its size, length and SHA-256.

## On the v1.0.0 release

`quran_data.db.gz`, `quran-page-fonts.zip` and one `<edition>.json` per tafsir or translation book.
They are release attachments, not files here: the database and fonts are larger than jsDelivr serves.

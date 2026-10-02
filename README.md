# The Desire of Ages

An English-language digital reader for *The Desire of Ages* by Ellen G. White.

## Features

- Complete 87-chapter text with page and paragraph references
- Full-text chapter and passage search
- Human-narrated audiobook with chapter navigation and playback speed controls
- Selection-based quote sharing with exact passage links
- Bookmarks, adjustable text size, and light/dark themes
- Responsive desktop and mobile layouts

## Run locally

Serve the project with any static file server:

```sh
python3 -m http.server 4173
```

Then open `http://localhost:4173`.

## Sources

- Book text: [EGW Writings](https://text.egwwritings.org/book/b130)
- Audiobook narrated by Mike McCabe: [Ellen White Audio](https://ellenwhiteaudio.org/desire-of-ages/). Used with permission from Uriel, as confirmed by the client.
- Homepage card artwork: supplied by the client.

Imported text has been normalized to remove extra spaces before punctuation following verse numbers (for example, `Psalm 65:6; 95:5.`). Wording, ellipses, and page/paragraph identifiers are unchanged.

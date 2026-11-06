# Tab card catalog

The card offers the [Tab](https://github.com/wesleymason) iOS app uses to recommend dining cards.

The app fetches `CardCatalog.json` from this repo at most once a day and keeps the newest copy it has seen, falling back to the copy bundled with the app. To publish new terms, update the file and bump its `updatedAt` (ISO 8601) and each changed card's `lastVerified`.

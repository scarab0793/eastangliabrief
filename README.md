# East Anglia Brief

A daily local news roundup for Norfolk and Suffolk, with a tab for each town:
Norwich, Great Yarmouth, King's Lynn, Lowestoft, Ipswich and Bury St Edmunds.

Each story is a short summary in our own words with a link to the original
source (local papers via NewsNow, and official council releases).

## How it works

- `index.html` is a single self-contained page (no build step).
- The stories live in the JSON block `<script type="application/json" id="news-data">`
  near the top of the file. To update the news, replace the contents of that block
  (`updated`, `note`, and each town's `items`).
- Tabs use the URL hash: `#all`, `#norwich`, `#great-yarmouth`, `#kings-lynn`,
  `#lowestoft`, `#ipswich`, `#bury`.

## Hosting

Works on any static host. For GitHub Pages: Settings → Pages → deploy from the
`main` branch, root folder.

## Notes

Summaries are paraphrased; read the full story at the publisher. Links to local
papers open via the NewsNow aggregator, and some articles are behind the
publisher's paywall.

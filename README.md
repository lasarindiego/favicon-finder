# Favicon Finder

A tiny, no-backend tool to fetch website favicons - built to fix password
manager items (originally 1Password) that show generic or missing icons.

## What it does

- Type a domain and instantly get its favicon.
- Paste or import a list in bulk - it reads Title + URL columns, so a
  1Password export works out of the box, or any plain CSV/XLSX with a
  title and a domain column.
- Download icons one by one, or grab everything selected as a single `.zip`.
- Available in English and Portuguese (toggle top right); your choice and
  your list are remembered locally between visits.
- 100% client-side. No login, no backend, no data ever leaves your browser.

## Why

Icons for niche sites, internal tools, and work logins are often missing or
ugly in password managers. This pulls a clean favicon for anything with a
domain, in bulk, without doing it one by one by hand.

## Credits

- Icons via the free, public [favicon.im](https://favicon.im) API.
- [wsrv.nl (weserv)](https://wsrv.nl) is used as a CORS-friendly fallback
  when a direct request is blocked, so bulk downloads still work.

Both are free public services this project doesn't control or guarantee the
availability of - many thanks to both for offering them.

## License

MIT - see [LICENSE](./LICENSE).

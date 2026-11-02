# EOTWSG Newsletter Images

Permanent image hosting for **Grid-Down Weekly** (the EOTWSG newsletter) and its
blog mirrors on [eotwsg.blogspot.com](https://eotwsg.blogspot.com).

## Why this repo exists

Newsletter hero and item images must never live on temporary or expiring links.
This public repository is the permanent home for them. Images here are served
over HTTPS and do not expire.

## Layout

One folder per issue, named by the issue's Monday date (`YYYY-MM-DD`):

| Folder | Contents |
|---|---|
| `2026-10-12/` | Issue Four hero + 5 item images |
| `2026-10-19/` | Issue Five hero + 3 item images |
| `2026-10-26/` | Issue Five review-cycle hero (site archive copy) |
| `2026-11-02/` | Issue Six hero |

New issues: add a new dated folder with `hero.jpg` and any `item-*.jpg` files.

## Permanent URLs

Use the raw GitHub URL for any file:

```
https://raw.githubusercontent.com/autosponsor/eotwsg-newsletter-images/main/<YYYY-MM-DD>/<file>.jpg
```

Example — Issue Six hero:

```
https://raw.githubusercontent.com/autosponsor/eotwsg-newsletter-images/main/2026-11-02/hero.jpg
```

A CDN mirror of the same files is also available via jsDelivr:

```
https://cdn.jsdelivr.net/gh/autosponsor/eotwsg-newsletter-images@main/<YYYY-MM-DD>/<file>.jpg
```

## Rules

- Never delete or rename a published image — blog posts and sent emails link to
  these URLs permanently.
- To fix an image, add a new file (e.g. `hero-v2.jpg`) rather than overwriting
  in place where a link is already live.

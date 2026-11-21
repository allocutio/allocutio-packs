# Allocutio Packs

Public list of content packs and exam/practice content for the Allocutio English learning app.

**Status:** no packs are listed yet. `packs.json` is an empty list until each pack passes the listing procedure below.

## What is here

| File | Purpose |
|---|---|
| `packs.json` | The pack list that the app reads (settings > content packs > community packs). Empty for now. |
| `LISTING.md` | How a pack gets listed, re-checked and delisted. |

## How the app uses it

The app downloads a listed pack as a zip over HTTPS and checks its sha256 before installing it. The app does not clone Git repositories. After download, the app runs its own static pack checks, and your learning progress is kept per pack.

## Licences

Each listed pack states its own licence in its entry and in its bundle. No pack content is published here before its licence has been checked.

Korean: [README.ko.md](README.ko.md)

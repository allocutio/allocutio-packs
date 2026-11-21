# Listing procedure

A pack is listed in `packs.json` only after all of the following:

1. **Licence check.** The pack's licence and every source licence are confirmed and stated.
2. **Static checks.** The bundle passes the shared pack linter (structure and item rules).
3. **AI quality check.** A local AI review scores 85% or more (CONTENT-PACKS §8). Below 85%, the listing is held.
4. **Download entry.** The entry gives an HTTPS zip URL and its sha256. Git URLs are not used.

## Re-checks and delisting

- Every listed pack is re-checked every 7 days on a local machine. No hosted CI runner is used.
- Two failed re-checks in a row make a pack a delisting candidate. Delisting is a recorded decision; it does not happen automatically.
- A delisted pack stays installed on devices that already have it. The app only marks it as removed from the list.

## Warnings

A missing `not_when` rule sentence is counted as a warning for now. It is not a blocker yet.

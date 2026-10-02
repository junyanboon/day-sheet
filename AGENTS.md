# Repository instructions

## Standing authorization — day-sheet operational documentation

Junyan, September 9, 2026: “Yes you can. Update it so you always have authorization.” Junyan subsequently explicitly confirmed saving permission for day-sheet operational documentation only in the repository instructions and docket skill. This standing ruling authorizes the documentation publishing and merging steps below.

Agents have standing authorization to create branches, commit, push, open and merge PRs, and publish verified operational documentation and deployment notes to `junyanboon/day-sheet`, including `plumbing.html`. This includes the relevant service behavior, message routes, evidence model, cadence, failure handling, revision and validation results needed to document authorized work. Do not request fresh approval merely because this documentation is published to the day-sheet repository. Check concurrent work, preserve unrelated content and verify the published result.

This authorization covers operational documentation publication; separate customer-message release, cash movement and production behavior changes continue to follow their applicable authorization. Never publish credentials, access codes or unnecessary personal details. This ruling does not override tool-enforced restrictions.

## Plumbing Map change log: no PRs here for entries (Junyan, 2026-10-02, d34 to d36)

Do not open a PR in this repo to add a change-log entry to `plumbing.html`. Each plumbing change adds one file, `plumbing/changes/YYYY-MM-DD-short-slug.md`, in the same PR as the change, in `desk-correspondence` or `deck-app` (format: `desk-correspondence/plumbing/README.md`). The render job (`.github/workflows/render.yml`) builds the list between `<!-- changes:start -->` and `<!-- changes:end -->` every 15 minutes and keeps `plumbing-index.json`; never hand-edit either. The list under "Up to 2026-10-02" is frozen. A PR here is still right for the map drawings at the top of the page.

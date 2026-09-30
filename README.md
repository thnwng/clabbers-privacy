# clabbers-privacy

The privacy policy page for the Clabbers app (`dev.clabbers.app`), required by the
Google Play listing. One self-contained `index.html`, no build step, no dependencies.

- **Live URL:** https://thnwng.github.io/clabbers-privacy/
- **Publishes via:** GitHub Pages from `main`, repo root. **push = publish** — any push
  to `main` changes the live page with no further step, so pushes are owner-approved
  only (workspace-change-control).
- **To update:** edit `index.html`, bump the "Effective" date in the header line if the
  policy's substance changed, commit, push (with approval).

This URL is referenced by: the Google Play Console listing (privacy policy field) and
the Play data safety form (account-deletion request link). The deletion-request resource
is section 14, "Deleting your account and data", anchor `#delete` (from the full rewrite,
commit `f532555`; before it, the "Data retention and deleting your data" section): it gives
the in-app path AND an email path that needs no reinstall, as Play's account-deletion rule
requires. If this repo is ever renamed or moved, update those Console fields the same day —
GitHub does not redirect Pages URLs on rename (the 2026-07-25 match-pairing incident).

Created 2026-08-15 (owner-approved: "page") for the Play publishing campaign — see
`E:\Claude\.context\Clabbers-clabbers.md`, Answers ("GOOGLE PLAY: PUBLISH").

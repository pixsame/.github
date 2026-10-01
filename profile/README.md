# pixsame

*Pix* as in pixel, *same* as in identical.

Visual regression testing that catches the pixels that changed and lets you approve the ones that should have. One run manifest, shared by every runner, so the same CI tooling works whichever test framework you use.

- [`@frsource/cypress-plugin-visual-regression-diff`](https://github.com/pixsame/cypress-plugin-visual-regression-diff) – the Cypress plugin, with a GUI for reviewing diffs (becomes `@pixsame/cypress` in 6)
- [`@pixsame/playwright`](https://github.com/pixsame/cypress-plugin-visual-regression-diff/tree/main/packages/playwright-visual-regression-diff) – the same flow for Playwright, with an optional remote browser in Docker
- [`@pixsame/manifest`](https://www.npmjs.com/package/@pixsame/manifest) – the run manifest as a free standard: JSON Schema, types, reader, merger, converters
- [pixsame for GitHub](https://github.com/pixsame/cypress-plugin-visual-regression-diff/tree/main/packages/github-app) – a GitHub App that turns the manifest into a check run, a PR comment with old / diff / new thumbnails and an **Approve** button

Website: [pixsame.com](https://pixsame.com) · Sponsor the work: [GitHub Sponsors](https://github.com/sponsors/FRSgit), [Patreon](https://www.patreon.com/frsource), [Buy Me a Coffee](https://www.buymeacoffee.com/FRSOURCE)
